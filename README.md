# How to use
1. Download the template file
2. Move it to `~/Library/Developer/Xcode/Templates/Project Templates/` folder:
```bash
# assuming that you are currently in the directory with the downloaded template
mkdir -p ~/Library/Developer/Xcode/Templates/Project\ Templates; mv UIKit\ App\ \(no\ storyboard\).xctemplate $_
```
3. Now it should be available in the Xcode menu: File -> New -> Project under the "Project Templates" category.

# Limitations
- Objective-C is not supported (although it can be chosen because this template inherits from the default single view app template).

# Useful reads
- https://useyourloaf.com/blog/creating-custom-xcode-project-templates/
- https://www.kodeco.com/26582967-xcode-project-and-file-templates
