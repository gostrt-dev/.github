# [gostrt](https://www.gostrt.dev)

<center><img src="doc/assets/logo.jpg" style="width: 0%; height: auto;"></center>

What if starting a new go project were as simple as `$ go start rest-service`, `$ go start cli`, or `$ go start library`? If you're like me, then you're probably thinking:

> That would be great if there was a tool that didn't impose horribly opinionated takes on application design.

`gostrt` is a tool to short-circuit the process of bootstrapping idiomatic Go projects in standardized way.

**The standards are up to you!**

Extensibility is *the* core design principle at the heart of `gostrt`. importantly, to streamline the authoring, managing, exploring, and publishing of the standards themselves.

### Built on Go's Foundations

At its heart, `gostrt` leverages the `text/template` package from Go's standard library, infusing it with additional capabilities specifically aimed at Go developers. It enriches the foundational text generation provided by `text/template`, allowing for intricate Go expressions to be dynamically integrated within templates. This includes support for variable insertion, conditional logic, iteration, and the incorporation of custom functions, presented through a familiar Go-centric syntax.

`gostrt` introduces a CLI for straightforward template management, enriches the syntax for better alignment with Go idioms, and establishes a communal platform for the sharing of templates. Essentially, it's `text/template` enhanced with tools and features that resonate with the daily workflows of Go developers, making it an indispensable asset for generating Go modules more efficiently.

### Standardization Use Cases

One of the paramount goals of `gostrt` is to foster standardization within engineering organizations. It aims to serve as a pivotal tool for teams to craft reproducible solutions that adhere to company or organization-specific standards. Here's how `gost` contributes to standardization:

- **Consistent Project Structures**: `gostrt` templates can define a standardized project layout, ensuring that all projects within an organization start with a consistent file and directory structure, naming conventions, and basic setup. This consistency simplifies onboarding for new developers and streamlines the maintenance process.
  
- **Enforcing Coding Practices**: Templates can include boilerplate code that follows best practices and coding standards specific to the organization. This ensures that every new project automatically adheres to these standards, reducing the need for extensive code reviews focused on style and convention compliance.

- **Reusable Components**: `gostrt` allows teams to create templates for commonly used components or modules within their organization. This facilitates the reuse of code that has been vetted and approved, reducing duplication of effort and ensuring that solutions are built on proven, reliable foundations.

- **Custom Functionality for Organization Needs**: Through the integration of custom functions within templates, `gost` enables organizations to encapsulate complex logic or domain-specific functionality that can be easily reused across projects. This feature supports the creation of templates that not only scaffold a project but also imbue it with the organization's unique business logic or infrastructure setup.

- **Shared Template Repositories**: `gostrt` offers a default set of repository templates out of the box, but the real magic begins when you start your own custom template repository.
- custom template repos can be published publicly or they can be maintained privately by organizations to establish a centralized collection of standard templates that as a single source of truth for project setups, ensuring that every team has access to the latest, approved approach for Go projects.

In essence, `gostrt` is not just a tool for generating Go code—it's a framework for embedding and disseminating organizational knowledge and standards. By leveraging `gostrt`, engineering organizations can ensure that every new project is not just a fresh start, but a continuation of a tradition of excellence, efficiency, and standardization.

## Get started with `gostrt`!

