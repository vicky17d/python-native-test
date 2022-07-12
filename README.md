This plugin is to test the native gradle import for Python plugins

module under test - python-module
parent module needs to apply the ext plugin as well
```
plugins {
    id "org.jetbrains.gradle.plugin.idea-ext" version "1.1.5"
}

```

### How to check everything is set up correctly
- python-module should have Python module icon\

Also Check the corresponding .iml file for 
- type="PYTHON_MODULE"
- ```
    <component name="ReSTService">
    <option name="DOC_DIR" value="$MODULE_DIR$/docs" />
      </component> 
    <component name="TestRunnerService"> 
        <option name="PROJECT_TEST_RUNNER" value="pytest" />
     </component>

