setp 1
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
setop 2
dependencies {
		implementation 'com.github.User:Repo:Tag'
}
that's all.
