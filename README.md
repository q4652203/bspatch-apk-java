# bspatch-apk-java
合并apk差分包
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
dependencies {
  implementation 'com.github.q4652203:bspatch-apk-java:Tag'
}
