# C# Source Generators

A list of C# Source Generators (not necessarily awesome), because I haven't found a good list yet.

**C# Source Generators** is a Roslyn compiler feature introduced in C#9/.NET 5. It lets C# developers inspect user code and generate new C# source files that can be added to a compilation.

Add GitHub topic [`csharp-sourcegenerator`](https://github.com/topics/csharp-sourcegenerator) to your generator repo - let's get it started!

## Documentation and samples

- [docs.microsoft.com](https://docs.microsoft.com/en-us/dotnet/csharp/roslyn-sdk/source-generators-overview) official documentation.
- [dotnet/roslyn feature design document](https://github.com/dotnet/roslyn/blob/master/docs/features/source-generators.md) describing the compiler feature.
- [dotnet/roslyn cookbook](https://github.com/dotnet/roslyn/blob/master/docs/features/source-generators.cookbook.md) to help with generator creation.
- [dotnet/roslyn-sdk samples](https://github.com/dotnet/roslyn-sdk/tree/master/samples/CSharp/SourceGenerators) show how to implement a source generator and use features like external package references (*inside* generators). Includes AutoNotify, Csv, Maths, Mustache, and SettingsXml.
- [sourcegen.dev](https://sourcegen.dev) - an online Source Generator Playground to play with generator ideas 💡 without any setup noise. [Source repo](https://github.com/davidwengier/SourceGeneratorPlayground).
- [davidwengier/SourceGeneratorTemplate](https://github.com/davidwengier/SourceGeneratorTemplate)  - ![stars](https://img.shields.io/github/stars/davidwengier/SourceGeneratorTemplate?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/davidwengier/SourceGeneratorTemplate?style=flat-square&cacheSeconds=86400) A basic template for writing a C# source generator, from the Roslyn dev.

## Source Generators

<!--
Template for entries:
- [REPO](https://github.com/REPO) - ![stars](https://img.shields.io/github/stars/REPO?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/REPO?style=flat-square&cacheSeconds=86400)
-->

- [AnyOf](https://github.com/StefH/AnyOf) - ![stars](https://img.shields.io/github/stars/StefH/AnyOf?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/StefH/AnyOf?style=flat-square&cacheSeconds=86400) https://github.com/nemesissoft/Nemesis.TextParsers) The Source Generator creates a `AnyOf<First, TSecond, ...>` type to handle multiple defined types as input parameters for methods.
- [AutoDeconstructable](https://github.com/nemesissoft/Nemesis.TextParsers/tree/master/Nemesis.TextParsers.CodeGen/Deconstructable)  - ![stars](https://img.shields.io/github/stars/nemesissoft/Nemesis.TextParsers?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/nemesissoft/Nemesis.TextParsers?style=flat-square&cacheSeconds=86400) Generator for efficient and automatic flat text serializer/deserializer using [Deconstructable aspect](https://github.com/nemesissoft/Nemesis.TextParsers/blob/master/Specification.md#deconstructables) in [NTP](https://github.com/nemesissoft/Nemesis.TextParsers) library.
- [AutoInterface](https://github.com/beakona/AutoInterface)  - ![stars](https://img.shields.io/github/stars/beakona/AutoInterface?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/beakona/AutoInterface?style=flat-square&cacheSeconds=86400) interface-to-member source generator.
- [Avalonia.NameGenerator](https://github.com/AvaloniaUI/Avalonia.NameGenerator)  - ![stars](https://img.shields.io/github/stars/avaloniaui/Avalonia.NameGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/avaloniaui/Avalonia.NameGenerator?style=flat-square&cacheSeconds=86400) Generates typed references to named [Avalonia](https://github.com/avaloniaui) XAML controls.
- [avatar](https://github.com/kzu/avatar)  - ![stars](https://img.shields.io/github/stars/kzu/avatar?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/kzu/avatar?style=flat-square&cacheSeconds=86400) A modern compile-time generated interception/proxy library.
- [Azura](https://github.com/Lucina/Azura)  - ![stars](https://img.shields.io/github/stars/Lucina/Azura?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Lucina/Azura?style=flat-square&cacheSeconds=86400) Generates binary [de]serializers on Streams at design time.
- [boilerplatezero](https://github.com/IGood/boilerplatezero)  - ![stars](https://img.shields.io/github/stars/IGood/boilerplatezero?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/IGood/boilerplatezero?style=flat-square&cacheSeconds=86400) WPF Dependency Property Generator.
- [Cloneable](https://github.com/mostmand/Cloneable)  - ![stars](https://img.shields.io/github/stars/mostmand/Cloneable?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/mostmand/Cloneable?style=flat-square&cacheSeconds=86400) auto-generate Clone method.
- [CrossLink](https://github.com/archi-Doc/CrossLink)  - ![stars](https://img.shields.io/github/stars/archi-Doc/CrossLink?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/archi-Doc/CrossLink?style=flat-square&cacheSeconds=86400) A C# Library for creating and managing multiple links between objects.
- [Data Builder Generator](https://github.com/dasMulli/data-builder-generator)  - ![stars](https://img.shields.io/github/stars/dasMulli/data-builder-generator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/dasMulli/data-builder-generator?style=flat-square&cacheSeconds=86400) Generate data builder patterns for your model classes.
- [DevExpress.Mvvm.CodeGenerators](https://github.com/DevExpress/DevExpress.Mvvm.CodeGenerators) - ![stars](https://img.shields.io/github/stars/DevExpress/DevExpress.Mvvm.CodeGenerators?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/DevExpress/DevExpress.Mvvm.CodeGenerators?style=flat-square&cacheSeconds=86400) Generates boilerplate code for your View Models (INotifyPropertyChanged, Commands, IDataErrorInfo, DevExpress services).
- [dotVariant](https://github.com/mknejp/dotvariant) - ![stars](https://img.shields.io/github/stars/mknejp/dotvariant?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/mknejp/dotvariant?style=flat-square&cacheSeconds=86400) A type-safe and space-efficient sum type for C# (comparable to discriminated unions in C or C++).
- [Durian](https://github.com/piotrstenke/Durian) - ![stars](https://img.shields.io/github/stars/piotrstenke/Durian?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/piotrstenke/Durian?style=flat-square&cacheSeconds=86400) Extends the default capabilities of C# by mimicking features from other languages.
- [EnumFastToStringDotNet](https://github.com/Spinnernicholas/EnumFastToStringDotNet)  - ![stars](https://img.shields.io/github/stars/Spinnernicholas/EnumFastToStringDotNet?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Spinnernicholas/EnumFastToStringDotNet?style=flat-square&cacheSeconds=86400) - Automatically generates enum extension methods that implement a switch expression based ToString method.
- [Fairy](https://github.com/hermanussen/Fairy)  - ![stars](https://img.shields.io/github/stars/hermanussen/Fairy?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/hermanussen/Fairy?style=flat-square&cacheSeconds=86400) generates C# code based on Sitecore Content Serialization (SCS) `.yml` files.
- [Flattening](https://github.com/Kros-sk/Kros.Generators.Flattening) - ![stars](https://img.shields.io/github/stars/Kros-sk/Kros.Generators.Flattening?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Kros-sk/Kros.Generators.Flattening?style=flat-square&cacheSeconds=86400) - C# source generator for generating flattened classes from complex domain classes.
- [FluentBuilder](https://github.com/StefH/FluentBuilder) - ![stars](https://img.shields.io/github/stars/StefH/FluentBuilder?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/StefH/FluentBuilder?style=flat-square&cacheSeconds=86400) - A project which uses Source Generation to create a FluentBuilder for a specified model or DTO.
- [Generator.Equals](https://github.com/diegofrata/Generator.Equals)  - ![stars](https://img.shields.io/github/stars/diegofrata/Generator.Equals?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/diegofrata/Generator.Equals?style=flat-square&cacheSeconds=86400) generates equality and hashing for classes and records, supports a number of strategies for comparing collections and properties.
- [GitBuildInfo.SourceGenerator](https://github.com/Elskom/GitBuildInfo.SourceGenerator)  - ![stars](https://img.shields.io/github/stars/Elskom/GitBuildInfo.SourceGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Elskom/GitBuildInfo.SourceGenerator?style=flat-square&cacheSeconds=86400) - for dumping the git information (commit hash, branch, the head description) into assembly level metadata attributes.
- [GraphQL.Tools](https://github.com/MoienTajik/GraphQL.Tools)  - ![stars](https://img.shields.io/github/stars/MoienTajik/GraphQL.Tools?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/MoienTajik/GraphQL.Tools?style=flat-square&cacheSeconds=86400) - A GraphQL to C# compiler (code-generator) which turns your GraphQL schema into a set of C# classes, interfaces, and enums.
- [HttpClientCodeGenerator](https://github.com/Jalalx/HttpClientCodeGenerator)  - ![stars](https://img.shields.io/github/stars/jalalx/HttpClientCodeGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/jalalx/HttpClientCodeGenerator?style=flat-square&cacheSeconds=86400) - HttpClientGenerator is a tool that uses the Roslyn code generator feature to write boilerplate HttpClient code for you.
- [IDisposableGenerator](https://github.com/Elskom/IDisposableGenerator)  - ![stars](https://img.shields.io/github/stars/Elskom/IDisposableGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Elskom/IDisposableGenerator?style=flat-square&cacheSeconds=86400) - a Source Generator for Generating the Dispose functions in Disposables. All you have to do is mark them with attributes and it will work from there.
- [Imp.NET](https://github.com/DouglasDwyer/Imp.NET)  - ![stars](https://img.shields.io/github/stars/DouglasDwyer/Imp.NET?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/DouglasDwyer/Imp.NET?style=flat-square&cacheSeconds=86400) - a fast, high-level, object-oriented C# networking library that supports the invocation of remote methods through proxy interface objects.
- [IoTHubClientGenerator](https://github.com/alonf/IoTHubClientGenerator) -  ![stars](https://img.shields.io/github/stars/alonf/IoTHubClientGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/alonf/IoTHubClientGenerator?style=flat-square&cacheSeconds=86400) Build a C# Azure IoT Device client program in seconds!
- [Jab](https://github.com/pakrym/jab)  - ![stars](https://img.shields.io/github/stars/pakrym/jab?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/pakrym/jab?style=flat-square&cacheSeconds=86400) - Compile Time Dependency Injection
- [JsonByExampleGenerator](https://github.com/hermanussen/JsonByExampleGenerator)  - ![stars](https://img.shields.io/github/stars/hermanussen/JsonByExampleGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/hermanussen/JsonByExampleGenerator?style=flat-square&cacheSeconds=86400) - generate classes based on example json files in your project.
- [JsonSrcGen](https://github.com/trampster/JsonSrcGen)  - ![stars](https://img.shields.io/github/stars/trampster/JsonSrcGen?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/trampster/JsonSrcGen?style=flat-square&cacheSeconds=86400) - compile time JSON serializer generation.
- [kli.Localize](https://github.com/kl1mm/localize) - ![stars](https://img.shields.io/github/stars/kl1mm/localize?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/kl1mm/localize?style=flat-square&cacheSeconds=86400) - localize strings from json files via  source code generation
- [lambdajection](https://github.com/cythral/lambdajection)  - ![stars](https://img.shields.io/github/stars/cythral/lambdajection?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/cythral/lambdajection?style=flat-square&cacheSeconds=86400) Framework for building AWS Lambdas using dependency injection and aspect-oriented programming.
- [Lazysh](https://github.com/B1Z0N/LazyshGen) - ![stars](https://img.shields.io/github/stars/B1Z0N/LazyshGen?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/B1Z0N/LazyshGen?style=flat-square&cacheSeconds=86400) Lazy implementation of any interface.
- [MapTo](https://github.com/mrtaikandi/MapTo)  - ![stars](https://img.shields.io/github/stars/mrtaikandi/mapto?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/mrtaikandi/mapto?style=flat-square&cacheSeconds=86400) - A convention based object to object mapper similar to Automapper.
- [MemberAccessGenerator](https://github.com/ufcpp/MemberAccessGenerator)  - ![stars](https://img.shields.io/github/stars/ufcpp/MemberAccessGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/ufcpp/MemberAccessGenerator?style=flat-square&cacheSeconds=86400) generates `GetMember(int)` and/or `GetMember(string)` methods that return property value for a given property name or index (e.g. in positional records).
- [MiniRazor](https://github.com/Tyrrrz/MiniRazor)  - ![stars](https://img.shields.io/github/stars/Tyrrrz/MiniRazor?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Tyrrrz/MiniRazor?style=flat-square&cacheSeconds=86400) Portable Razor compiler & code generator.
- [MockableStaticGenerator](https://github.com/HamedFathi/MockableStaticGenerator) - ![stars](https://img.shields.io/github/stars/HamedFathi/MockableStaticGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/HamedFathi/MockableStaticGenerator?style=flat-square&cacheSeconds=86400) A C# source generator to make an interface and a class wrapper to test static/extension methods.
- [MockGen](https://github.com/thomas-girotto/MockGen) - ![stars](https://img.shields.io/github/stars/thomas-girotto/MockGen?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/thomas-girotto/MockGen?style=flat-square&cacheSeconds=86400) A C# mocking library based on source generators.
- [MockSourceGenerator](https://github.com/hermanussen/MockSourceGenerator) - ![stars](https://img.shields.io/github/stars/hermanussen/MockSourceGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/hermanussen/MockSourceGenerator?style=flat-square&cacheSeconds=86400) A C# mocking library that generates mocks at compile-time using a source generator.
- [MrMeeseeks.ResXToViewModelGenerator](https://github.com/Yeah69/MrMeeseeks.ResXToViewModelGenerator) - ![stars](https://img.shields.io/github/stars/Yeah69/MrMeeseeks.ResXToViewModelGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Yeah69/MrMeeseeks.ResXToViewModelGenerator?style=flat-square&cacheSeconds=86400) Takes ResX files and generates localization ViewModels for a more convenient usage of localization in MVVM projects.
- [MrMeeseeks.StaticDelegateGenerator](https://github.com/Yeah69/MrMeeseeks.StaticDelegateGenerator) - ![stars](https://img.shields.io/github/stars/Yeah69/MrMeeseeks.StaticDelegateGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Yeah69/MrMeeseeks.StaticDelegateGenerator?style=flat-square&cacheSeconds=86400) Maks static classes and members injectable as dependency by generating delegating interfaces and their implementing classes.
- [MvvmGen](https://github.com/thomasclaudiushuber/mvvmgen) - ![stars](https://img.shields.io/github/stars/thomasclaudiushuber/MvvmGen?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/thomasclaudiushuber/MvvmGen?style=flat-square&cacheSeconds=86400) A lightweight MVVM library for XAML applications that generates your ViewModels with a C# Source Generator.
- [net_automatic_interface](https://github.com/codecentric/net_automatic_interface)  - ![stars](https://img.shields.io/github/stars/codecentric/net_automatic_interface?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/codecentric/net_automatic_interface?style=flat-square&cacheSeconds=86400) .Net Core Source Generator for Automatic Interfaces.
- [Plastic](https://github.com/sang-hyeon/Plastic)  - ![stars](https://img.shields.io/github/stars/sang-hyeon/Plastic?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/sang-hyeon/Plastic?style=flat-square&cacheSeconds=86400) This project provides encapsulation of things like Domain, Application Rules, Business Rules or Business Logic in Application.
- [PrimaryConstructor](https://github.com/chaowlert/PrimaryConstructor)  - ![stars](https://img.shields.io/github/stars/chaowlert/PrimaryConstructor?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/chaowlert/PrimaryConstructor?style=flat-square&cacheSeconds=86400) Generate primary constructor from readonly fields.
- [PrimitiveStaticDataGenerator](https://github.com/iiweis/PrimitiveStaticDataGenerator)  - ![stars](https://img.shields.io/github/stars/iiweis/PrimitiveStaticDataGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/iiweis/PrimitiveStaticDataGenerator?style=flat-square&cacheSeconds=86400) for creating methods that return optimized `ReadOnlySpan<T>` static data from primitive values.
- [PrintMembersGenerator](https://github.com/Youssef1313/PrintMembersGenerator)  - ![stars](https://img.shields.io/github/stars/Youssef1313/PrintMembersGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Youssef1313/PrintMembersGenerator?style=flat-square&cacheSeconds=86400) helps re-defining C# record's PrintMembers method to force include/exclude certain members.
- [ProxyInterfaceGenerator](https://github.com/StefH/ProxyInterfaceSourceGenerator)  - ![stars](https://img.shields.io/github/stars/StefH/ProxyInterfaceSourceGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/StefH/ProxyInterfaceSourceGenerator?style=flat-square&cacheSeconds=86400) generate an interface and a Proxy class for classes. This makes it possible to wrap external classes which do not have an interface, in a Proxy class which makes it easier to Mock and use DI.
- [Pure.DI](https://github.com/DevTeam/Pure.DI) - ![stars](https://img.shields.io/github/stars/DevTeam/Pure.DI?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/DevTeam/Pure.DI?style=flat-square&cacheSeconds=86400) - dependency injection for .NET without any IoC/DI containers, frameworks, dependencies, and thus without any performance impact and side-effects.
- [ResXFileCodeGenerator](https://github.com/VocaDB/ResXFileCodeGenerator)  - ![stars](https://img.shields.io/github/stars/VocaDB/ResXFileCodeGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/VocaDB/ResXFileCodeGenerator?style=flat-square&cacheSeconds=86400) Generates strongly-typed resource classes for looking up localized strings.
- [ScenarioTests](https://github.com/koenbeuk/ScenarioTests)  - ![stars](https://img.shields.io/github/stars/koenbeuk/ScenarioTests?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/koenbeuk/ScenarioTests?style=flat-square&cacheSeconds=86400) Test your code like you would write a notebook. Simply and effective
- [SerdeDn (serde-sn)](https://github.com/agocke/serde-dn)  - ![stars](https://img.shields.io/github/stars/agocke/serde-dn?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/agocke/serde-dn?style=flat-square&cacheSeconds=86400) is a port of the popular [serde.rs](https://serde.rs/) Rust serialization/deserialization library to .NET. Basic cases are fully automated using a C# source generator.
- [SmallSharp](https://github.com/kzu/SmallSharp)  - ![stars](https://img.shields.io/github/stars/kzu/SmallSharp?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/kzu/SmallSharp?style=flat-square&cacheSeconds=86400) Create, edit and run multiple C# 9.0 top-level programs in the same project by just selecting the startup program from the start button.
- [SmartAnnotations](https://github.com/fiseni/SmartAnnotations)  - ![stars](https://img.shields.io/github/stars/fiseni/SmartAnnotations?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/fiseni/SmartAnnotations?style=flat-square&cacheSeconds=86400) A library that uses source generators to automatically generate data annotations for your models. It provides a strongly-typed mechanism (fluent like API) to define your annotation rules.
- [SourceInject](https://github.com/giggio/sourceinject/)  - ![stars](https://img.shields.io/github/stars/giggio/sourceinject?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/giggio/sourceinject?style=flat-square&cacheSeconds=86400) A source generator that allow you to generate your services for dependencies injection during compile time.
- [SpreadCheetah](https://github.com/sveinungf/spreadcheetah)  - ![stars](https://img.shields.io/github/stars/sveinungf/spreadcheetah?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/sveinungf/spreadcheetah?style=flat-square&cacheSeconds=86400) Create Excel files with a C# Source Generator for generating the rows.
- [SqlMarshal](https://github.com/kant2002/SqlMarshal)  - ![stars](https://img.shields.io/github/stars/kant2002/SqlMarshal?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/kant2002/SqlMarshal?style=flat-square&cacheSeconds=86400) Native AOT friendly-performant mini-ORM. Generation of wrappers for accessing SQL using ADO.NET.
- [StackXML](https://github.com/ZingBallyhoo/StackXML)  - ![stars](https://img.shields.io/github/stars/ZingBallyhoo/StackXML?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/ZingBallyhoo/StackXML?style=flat-square&cacheSeconds=86400) Stack based zero-allocation XML serializer and deserializer.
- [StringLiteralGenerator](https://github.com/ufcpp/StringLiteralGenerator)  - ![stars](https://img.shields.io/github/stars/ufcpp/StringLiteralGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/ufcpp/StringLiteralGenerator?style=flat-square&cacheSeconds=86400) for optimizing UTF-8 binaries.
- [StrongInject](https://github.com/YairHalberstadt/stronginject)  - ![stars](https://img.shields.io/github/stars/YairHalberstadt/stronginject?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/YairHalberstadt/stronginject?style=flat-square&cacheSeconds=86400) - compile time dependency injection for .NET.
- [StructPacker](https://github.com/RudolfKurka/StructPacker)  - ![stars](https://img.shields.io/github/stars/RudolfKurka/StructPacker?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/RudolfKurka/StructPacker?style=flat-square&cacheSeconds=86400) binary serializer that auto-generates C# serialization code to achieve peak runtime performance and efficiency.
- [Svg to C# Source Generators](https://github.com/wieslawsoltes/Svg.Skia)  - ![stars](https://img.shields.io/github/stars/wieslawsoltes/Svg.Skia?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/wieslawsoltes/Svg.Skia?style=flat-square&cacheSeconds=86400) SVGC compiles SVG drawing markup to C# using SkiaSharp as rendering engine. SVGC can be also used as codegen for upcoming C# 9 Source Generator feature.
- [ThisAssembly](https://github.com/kzu/ThisAssembly)  - ![stars](https://img.shields.io/github/stars/kzu/ThisAssembly?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/kzu/ThisAssembly?style=flat-square&cacheSeconds=86400) Exposes project and assembly level information as constants in the ThisAssembly class.
- [ToString](https://github.com/Burgyn/MMLib.ToString)  - ![stars](https://img.shields.io/github/stars/Burgyn/MMLib.ToString?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Burgyn/MMLib.ToString?style=flat-square&cacheSeconds=86400) - C# source generator for implementing `ToString` override like `record` type.
- [Transplator](https://github.com/atifaziz/Transplator)  - ![stars](https://img.shields.io/github/stars/atifaziz/Transplator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/atifaziz/Transplator?style=flat-square&cacheSeconds=86400) A simple C# source generator for text templates.
- [Tinyhand](https://github.com/archi-Doc/Tinyhand)  - ![stars](https://img.shields.io/github/stars/archi-Doc/Tinyhand?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/archi-Doc/Tinyhand?style=flat-square&cacheSeconds=86400) - Tiny and simple data format/serializer using a source generator.
- [ValueChangedGenerator](https://github.com/ufcpp/ValueChangedGenerator)  - ![stars](https://img.shields.io/github/stars/ufcpp/ValueChangedGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/ufcpp/ValueChangedGenerator?style=flat-square&cacheSeconds=86400) for generating PropertyChanged from inner struct members.
- [ValueObjectGenerator](https://github.com/RyotaMurohoshi/ValueObjectGenerator)  - ![stars](https://img.shields.io/github/stars/RyotaMurohoshi/ValueObjectGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/RyotaMurohoshi/ValueObjectGenerator?style=flat-square&cacheSeconds=86400) C# source generator is for ValueObjects (ie.Wrapper classes).
- [WrapperValueObject](https://github.com/martinothamar/WrapperValueObject)  - ![stars](https://img.shields.io/github/stars/martinothamar/WrapperValueObject?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/martinothamar/WrapperValueObject?style=flat-square&cacheSeconds=86400) - for creating simple value objects wrapping primitive types.

## Tips & Tricks

Collection of tips and tricks (simple and brief to fit in Tweet):

[Tweeted](https://twitter.com/raboof/status/1397296571801288704) by [@raboof](https://twitter.com/raboof) on May 25 2021 at 23:00:

> TIL to debug a source generator in VS 16.10: upgrade [Microsoft.CodeAnalysis.CSharp to 3.10.\*](https://www.nuget.org/packages/Microsoft.CodeAnalysis.CSharp/3.10.0-3.final), add `<IsRoslynComponent>true</IsRoslynComponent>` to source generator project, select **Roslyn Component** for **Launch** in **Project Properties Debug** page, choose **Target** then <kbd>F5</kbd> :rocket:
>
> ![Source Generator debugger](https://docs.microsoft.com/en-us/visualstudio/releases/2019/media/16.10/16.10_p2_source_generators_debugger.png)

[Tweeted](https://twitter.com/raboof/status/1328426892882550784) by [@raboof](https://twitter.com/raboof) on Nov 16 2020 at 20:57:

> See files emitted by [#SourceGenerators] by adding these properties to your (*.csproj) project file:
>
> ```xml
> <EmitCompilerGeneratedFiles>true</EmitCompilerGeneratedFiles>
> <CompilerGeneratedFilesOutputPath>$(BaseIntermediateOutputPath)Generated</CompilerGeneratedFilesOutputPath>
> ```

[Tweeted](https://twitter.com/Chiser99/status/1301198611158499328) by [@Chiser99](https://twitter.com/Chiser99) on Sep 02 2020 at 06:41:

> I made a thing: https://github.com/chsienki/Kittitas
>
> If you're building Roslyn Source Generators or Analyzers check it out, it makes debugging them inside the compiler easier. #roslyn #csharp #dotnetcore #sourcegenerators #analyzers

Build failed in WPF projects [microsoft/CsWin32#7](https://github.com/microsoft/CsWin32/issues/7):

> If your build failed in a *_wpftmp.csproj file you need to add following property to your (*.csproj) project file:
> ```xml
> <IncludePackageReferencesDuringMarkupCompilation>true</IncludePackageReferencesDuringMarkupCompilation>
> ```
> 
> and use at least .NET 5.0.102 SDK

  [#SourceGenerators]: https://twitter.com/hashtag/SourceGenerators?src=hashtag_click
  [#sourcegenerators]: https://twitter.com/hashtag/sourcegenerators?src=hashtag_click
  [#roslyn]: https://twitter.com/hashtag/roslyn?src=hashtag_click
  [#csharp]: https://twitter.com/hashtag/csharp?src=hashtag_click
  [#dotnetcore]: https://twitter.com/hashtag/dotnetcore?src=hashtag_click
  [#analyzers]: https://twitter.com/hashtag/analyzers?src=hashtag_click

## Articles

<!-- Sorted from newest: -->

- [Using C# Source Generators to create an external DSL](https://devblogs.microsoft.com/dotnet/using-c-source-generators-to-create-an-external-dsl/) (2021-01-27) that shows how to implement a simple DSL.
- [4 ways to generate code in C# — Including Source Generators in .NET 5](https://levelup.gitconnected.com/four-ways-to-generate-code-in-c-including-source-generators-in-net-5-9e6817db425) (2021-01-19) demonstrates the comparison between Source Generators, T4 template and Reflection, etc.
- [.NET 5 Source Generators - MediatR - CQRS - OMG!](https://www.edument.se/en/blog/post/net-5-source-generators-mediatr-cqrs) (2020-12-16) explores how source generators can be used to automatically generate an API for a system using the MediatR library and the CQRS pattern.
- [Source Generators in .NET 5 with ReSharper](https://blog.jetbrains.com/dotnet/2020/11/12/source-generators-in-net-5-with-resharper/) (2020-11-20) introduces source generators and briefly mentions how they are being worked into the ReSharper product.
- [Source Generators - real world example](https://dominikjeske.github.io/source-generators) (2020-11-09) contains a rich and deep dive into a real world generator with lots of useful tips.
- [How to profile C# 9.0 Source Generators](https://jaylee.org/archive/2020/10/10/profiling-csharp-9-source-generators.html) (2020-10-10) demonstrates how to profile your source generator using the [performance profiling tools built into Visual Studio](https://docs.microsoft.com/en-us/visualstudio/profiling/?view=vs-2019).
- [How to Debug C# 9 Source Code Generators](https://nicksnettravels.builttoroam.com/debug-code-gen/) (2020-10-09) contains debugging tips.
- [How to generate code using Roslyn source generators in real world scenarios](https://www.cazzulino.com/source-generators.html) (2020-09-17) rich story of how ThisAssembly generator was written using Scriban templates.
- [.NET Blog 'New C# Source Generator Samples' post](https://devblogs.microsoft.com/dotnet/new-c-source-generator-samples/) (2020-08-25) that shows some simple samples.
- [.NET Blog 'Introducing C# Source Generators' post](https://devblogs.microsoft.com/dotnet/introducing-c-source-generators/) (2020-04-29) that announces the feature.

## Videos

<!-- Sorted from newest: -->

- [C# Source Generators - Write code that writes code - David Wengier](https://www.youtube.com/watch?v=pqLs7X6Cr6s) (2020-11-13) Roslyn dev takes deep dive into the topic.
- [.NET Languages and Runtime Community Standup - Source Generators](https://www.youtube.com/watch?v=A4479Etdx4I) (2020-10-08) shows how Generators work and how they can be tested.
- [Channel 9 'Source Generators in C#'](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Source-Generators-in-CSharp) (2020-08-12) has Roslyn PMs discussing the feature.

## Demo, PoC and excercise projects

Maybe they can inspire you too!

- [AutoCoder](https://github.com/beakona/AutoCoder) - ![stars](https://img.shields.io/github/stars/beakona/AutoCoder?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/beakona/AutoCoder?style=flat-square&cacheSeconds=86400) for effective and flexible object coding.
- [RyanAlameddine/SourceGeneratorDemo](https://github.com/RyanAlameddine/SourceGeneratorDemo) - ![stars](https://img.shields.io/github/stars/RyanAlameddine/SourceGeneratorDemo?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/RyanAlameddine/SourceGeneratorDemo?style=flat-square&cacheSeconds=86400) contains 3 demos: hello world, INPC and OpCode class.
- [TMC-CSharp/CodeExerciseLibrary](https://github.com/TMC-CSharp/CodeExerciseLibrary) - ![stars](https://img.shields.io/github/stars/TMC-CSharp/CodeExerciseLibrary?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/TMC-CSharp/CodeExerciseLibrary?style=flat-square&cacheSeconds=86400) Library to help creating C# exercises. Generates missing methods and classes inside tests on the fly by using Source Generators.
- [DpdtInject](https://github.com/lsoft/DpdtInject) - ![stars](https://img.shields.io/github/stars/lsoft/DpdtInject?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/lsoft/DpdtInject?style=flat-square&cacheSeconds=86400) DI container based on C# Source Generators. Its goal is to remove everything possible from runtime and make resolving process as faster as we can. This is achieved by transferring huge piece of resolving logic to the compilation stage into the source generator.
- [jakubsturc/talk-csharp-source-generators](https://github.com/jakubsturc/talk-csharp-source-generators/tree/master/demo/SourceGeneratorSamples) - ![stars](https://img.shields.io/github/stars/jakubsturc/talk-csharp-source-generators?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/jakubsturc/talk-csharp-source-generators?style=flat-square&cacheSeconds=86400) contains 4 generators: AutoNotify, ConsoleWritelineHijack, HelloWorld and SettingsXml, plus nice presentation slides.
- [Compile Time Method Execution Generator](https://github.com/hermanussen/CompileTimeMethodExecutionGenerator) - ![stars](https://img.shields.io/github/stars/hermanussen/CompileTimeMethodExecutionGenerator?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/hermanussen/CompileTimeMethodExecutionGenerator?style=flat-square&cacheSeconds=86400) proof of concept that allows executing a method during compilation, so that it can be really fast during runtime.

## Projects using custom Source Generators "internally"

- [Elskom/Sdk](https://github.com/Elskom/Sdk) - ![stars](https://img.shields.io/github/stars/Elskom/Sdk?style=flat-square$cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/Elskom/Sdk?style=flat-square&cacheSeconds=86400) Dumps git repository data to assembly level metadata attributes that can be checked at runtime for things like trapping if a user is using an possibly unstable build of the libraries built in the repository and so the user can see a message about it (and optionally opt into running the possibly unstable code).
- [NetFabric.Hyperlinq](https://github.com/NetFabric/NetFabric.Hyperlinq) - ![stars](https://img.shields.io/github/stars/NetFabric/NetFabric.Hyperlinq?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/NetFabric/NetFabric.Hyperlinq?style=flat-square&cacheSeconds=86400) generates overloads for its extension methods.
- [RestEase](https://github.com/canton7/RestEase) - ![stars](https://img.shields.io/github/stars/canton7/RestEase?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/canton7/RestEase?style=flat-square&cacheSeconds=86400) uses Source Generator to generate interface implementations on compile time instead of in runtime via Reflection.Emit.
- [WarHub/wham](https://github.com/WarHub/wham) - ![stars](https://img.shields.io/github/stars/WarHub/wham?style=flat-square&cacheSeconds=604800) ![last commit](https://img.shields.io/github/last-commit/WarHub/wham?style=flat-square&cacheSeconds=86400) generates code for immutable tree object graph based on red-green node approach used in Roslyn; generates custom XmlSerializer that supports C#9 records and ImmutableArray.
