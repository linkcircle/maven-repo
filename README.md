# maven-repo
1.project 的build.gradle中添加下面的maven
allprojects {
    repositories {
        maven { url "https://raw.githubusercontent.com/linkcircle/maven-repo/master" }
    }
}
