# Vapor 3 Simple Template

This is a basic template for new Vapor 3 projects, based on Paul Hudson's template at https://github.com/twostraws/vapor-clean

As Paul points out, this template offers a clean starting point for most real-world our team will create. It removes all the sample routes, handlers and other cruft that we always have to manually remove if we use one of Vapor's official templates.

The License is preconfigured with a standard MIT license and "Beezwax Datatools, Inc." as the copyright holder. 

## Usage

In the CLI, navigate to the desired parent directory for your project. Then create a new project with the Vapor toolbox:

``vapor new <ProjectName> --template=beezwax/vapor-3-simple-template``

As usual, cd into the new project directory and if needed, edit the project ``Package.swift`` file to add any desired dependencies. Thenbuild out the Vapor project assets with ``vapor build``, and create your Xcode project using ``vapor xcode -y``.

Last, in Xcode remember to select the "Run" schema > "MacOS" target and then build the project in Xcode. From there, you'll just need to create the Next Great Web App 😎
