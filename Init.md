Microsoft Visual Studio Solution File, Format Version 12.00
# Visual Studio 14
VisualStudioVersion = 14.0.25420.1
MinimumVisualStudioVersion = 10.0.40219.1
Project("{FAE04EC0-301F-11D3-BF4B-00C04F79EFBC}") = "NSaga", "NSaga\NSaga.csproj", "{E537D1BF-80A4-413B-A8F8-116C2A2382B1}"
EndProject
Project("{FAE04EC0-301F-11D3-BF4B-00C04F79EFBC}") = "Samples", "Samples\Samples.csproj", "{44FB286C-8589-4E87-AA69-861DCAEFD09F}"
EndProject
Project("{FAE04EC0-301F-11D3-BF4B-00C04F79EFBC}") = "Tests", "Tests\Tests.csproj", "{6A069A26-B930-49F5-B632-CBA186E5533E}"
EndProject
Project("{2150E333-8FDC-42A3-9474-1A3956D46DE8}") = "Solution Items", "Solution Items", "{1A30D447-9054-45CD-9FB6-A12779650349}"
	ProjectSection(SolutionItems) = preProject
		..\build.cake = ..\build.cake
		..\parameters.cake = ..\parameters.cake
		..\README.md = ..\README.md
		..\ReleaseNotes.md = ..\ReleaseNotes.md
		..\SolutionInfo.cs = ..\SolutionInfo.cs
	EndProjectSection
EndProject
Project("{FAE04EC0-301F-11D3-BF4B-00C04F79EFBC}") = "NSaga.SimpleInjector", "NSaga.SimpleInjector\NSaga.SimpleInjector.csproj", "{B8596EA9-B88B-4415-BC6F-CAD0EBF07A70}"
EndProject
Project("{FAE04EC0-301F-11D3-BF4B-00C04F79EFBC}") = "NSaga.Autofac", "NSaga.Autofac\NSaga.Autofac.csproj", "{5B7A00DC-75C7-4C94-820B-B449C427CD93}"
EndProject
Project("{FAE04EC0-301F-11D3-BF4B-00C04F79EFBC}") = "Tests.Benchmarking", "Tests.Benchmarking\Tests.Benchmarking.csproj", "{7E5DAAC9-EDCD-48EA-99EF-8C5541F38BB8}"
EndProject
Project("{FAE04EC0-301F-11D3-BF4B-00C04F79EFBC}") = "NSaga.AzureTables", "NSaga.AzureTables\NSaga.AzureTables.csproj", "{2A3BAD16-35B7-41BB-964F-453360535D89}"
EndProject
Project("{FAE04EC0-301F-11D3-BF4B-00C04F79EFBC}") = "NSaga.StructureMap", "NSaga.StructureMap\NSaga.StructureMap.csproj", "{84952E5A-1629-4B1D-A978-ED4356986D0A}"
EndProject
Global
	GlobalSection(SolutionConfigurationPlatforms) = preSolution
		Debug|Any CPU = Debug|Any CPU
		Release|Any CPU = Release|Any CPU
	EndGlobalSection
	GlobalSection(ProjectConfigurationPlatforms) = postSolution
		{E537D1BF-80A4-413B-A8F8-116C2A2382B1}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{E537D1BF-80A4-413B-A8F8-116C2A2382B1}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{E537D1BF-80A4-413B-A8F8-116C2A2382B1}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{E537D1BF-80A4-413B-A8F8-116C2A2382B1}.Release|Any CPU.Build.0 = Release|Any CPU
		{44FB286C-8589-4E87-AA69-861DCAEFD09F}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{44FB286C-8589-4E87-AA69-861DCAEFD09F}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{44FB286C-8589-4E87-AA69-861DCAEFD09F}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{44FB286C-8589-4E87-AA69-861DCAEFD09F}.Release|Any CPU.Build.0 = Release|Any CPU
		{6A069A26-B930-49F5-B632-CBA186E5533E}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{6A069A26-B930-49F5-B632-CBA186E5533E}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{6A069A26-B930-49F5-B632-CBA186E5533E}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{6A069A26-B930-49F5-B632-CBA186E5533E}.Release|Any CPU.Build.0 = Release|Any CPU
		{B8596EA9-B88B-4415-BC6F-CAD0EBF07A70}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{B8596EA9-B88B-4415-BC6F-CAD0EBF07A70}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{B8596EA9-B88B-4415-BC6F-CAD0EBF07A70}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{B8596EA9-B88B-4415-BC6F-CAD0EBF07A70}.Release|Any CPU.Build.0 = Release|Any CPU
		{5B7A00DC-75C7-4C94-820B-B449C427CD93}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{5B7A00DC-75C7-4C94-820B-B449C427CD93}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{5B7A00DC-75C7-4C94-820B-B449C427CD93}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{5B7A00DC-75C7-4C94-820B-B449C427CD93}.Release|Any CPU.Build.0 = Release|Any CPU
		{7E5DAAC9-EDCD-48EA-99EF-8C5541F38BB8}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{7E5DAAC9-EDCD-48EA-99EF-8C5541F38BB8}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{7E5DAAC9-EDCD-48EA-99EF-8C5541F38BB8}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{7E5DAAC9-EDCD-48EA-99EF-8C5541F38BB8}.Release|Any CPU.Build.0 = Release|Any CPU
		{2A3BAD16-35B7-41BB-964F-453360535D89}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{2A3BAD16-35B7-41BB-964F-453360535D89}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{2A3BAD16-35B7-41BB-964F-453360535D89}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{2A3BAD16-35B7-41BB-964F-453360535D89}.Release|Any CPU.Build.0 = Release|Any CPU
		{84952E5A-1629-4B1D-A978-ED4356986D0A}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{84952E5A-1629-4B1D-A978-ED4356986D0A}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{84952E5A-1629-4B1D-A978-ED4356986D0A}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{84952E5A-1629-4B1D-A978-ED4356986D0A}.Release|Any CPU.Build.0 = Release|Any CPU
	EndGlobalSection
	GlobalSection(SolutionProperties) = preSolution
		HideSolutionNode = FALSE
	EndGlobalSection
EndGlobal
