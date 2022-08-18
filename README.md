# onestopstudiox-ads-sdk
To get a Git project into your build:

Step 1(For old projects). Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
 Step 1(For New projects). Add the JitPack repository to your build file
 
  Add it in your root settings.gradle :
  
    dependencyResolutionManagement
    {
    ...
  	  repositories 
   		 {
		 ...
       		 maven { url 'https://jitpack.io' }
    		}
	}
  
  
  
  
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.onestopstudiox:onestopstudiox-ads-sdk:1.1.1'
	}
