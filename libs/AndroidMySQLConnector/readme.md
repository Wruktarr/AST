## Android MySQL Connector
**.AAR** dependency built from [@Android-MySQL-Connector](https://github.com/BoardiesITSolutions/Android-MySQL-Connector).

Please read more about how to use library here: [@Android-MySQL-Connector > Using the Library](https://github.com/BoardiesITSolutions/Android-MySQL-Connector#using-the-library)

#### Supported MySQL Versions
###### Currently
* 5.1.72
* 5.5.59
* 5.6.39
* 5.7.22

###### In development
* 8.0+

#### Adding dependency to your project
* _Create Android Studio project_
* Download 'AndroidMySQLConnector.aar'
* Put file in your project's **libs** folder
* Replace following line in your project's **app\grade.build**:
  ```
  dependencies {
    implementation fileTree(include: ['*.jar'], dir: 'libs')
    ...
  ```
* Replace it by this:
  ```
  dependencies {
    implementation fileTree(include: ['*.jar', '*.aar'], dir: 'libs')
    ...
  ```
* Ready to use!
