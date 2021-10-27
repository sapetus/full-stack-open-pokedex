CI/CD for C#

Use SonarLint for linting.
	-Available as an IDE extension and as a NuGet package (SonarAnalyzer.CSharp).
	-NuGet package is recommended for team settings, as it is automatically downloaded
	 during build.
	-Can spot bugs, vulnerabilities, and code smells.

There are multiple available testing frameworks, depending on the needs of the developers one might choose...
	-NUnit
		-Older, more 'mature' framework, lots of available documentation, and a large community.
	-XUnit
		-More modern version of NUnit, gaining traction in .NET community.
	-MSTest
		-Is shipped along with Visual Studio, but also available as a NuGet package (MSTest.TestFramework)

Again, there are multiple available tools for the build process. These tools can be used in isolation, or in conjunction with each other.
	-NAnt
		-Free and open source
	-MSBuild
		-Free and open source, bundled with Visual Studio
	-CruiseControl.NET (CCNet)
		-Free and open source
	-FinalBuilder
		-Commercial
	-PSake

In addition to Jenkins and GitHub Actions, other tools for CI/CD are for example...
	-CircleCI
		-Self hosted and cloud version available
	-Team City
		-Self hosted only
	-Bamboo
		-Self hosted and cloud version available

In this particular example, it is hard to say whether self hosted or cloud solution is better. 
Application is in late development, and six people are working on it, so there may be quite a discrepancy between
the know-how of developers. It might be a good idea to gather all developers together to discuss different
possibilities for moving forward.