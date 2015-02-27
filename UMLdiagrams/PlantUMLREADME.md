# PlantUML README

```
Note: this is a command line walk thru
```

```
Pre-run install plantuml.jar 2.5M
You need this, then make a directory for it and put it in there, then make your plantuml files in that same directory with a reference to the image file type (tpng for example) and .txt extension
```

1. Draft a UML script using the syntax native to PlantUML and save. For example, this file called SampleUseCase.txt:
	
	```
	@startuml

	(First usecase)
	(Another usecase) as (UC2)
	usecase UC3
	usecase (Last\nusecase) as UC4

	@enduml
	```
2. Make sure you have your plantuml.jar located, organized in a folder where you can find it. Run this command: `java -jar plantuml.jar tpng SampleUseCase.txt`

	**NOTE**