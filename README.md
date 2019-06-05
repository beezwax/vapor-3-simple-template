# Vapor 3 Simple Template

This is a basic template for new Vapor 3 projects, based on Paul Hudson's template at https://github.com/twostraws/vapor-clean

As Paul points out, this is likely the best starting point for most real-world our team will create, as it removes all the sample routes, handlers et al that we always have to remove using Vapor's standard templates.

The License is configured with standard MIT license, with Beezwax as the copyright holder. Update as needed for specific projects.

## Usage

In the CLI, navigate to the desired parent directory for your project. Then create a new project using the Vapor toolbox:

``vapor new <ProjectName> --template=beezwax/vapor-3-simple-template``

As usual, after editing the project ``Package.swift`` file to add any desired dependencies, you'll need to build out assets with ``vapor build``, and then create your Xcode project using ``vapor xcode -y``. 

Finally in Xcode, remember to select the Run schema > MacOS target and then build. From there, just create the Next Great Web App 😎