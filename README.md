How to include

Add it in your root build.gradle at the end of repositories:

```groovy
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
Add the dependency
  
```groovy
dependencies {
	   compile 'com.github.DEADMC:WizardStepView:1.0'
}
```
