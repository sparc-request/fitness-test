## How to run:
1. Open a terminal/command prompt session in the folder containing `fitnesse-standalone.jar`.
2. Paste the following command into your terminal/command prompt:  
```
  java -Xmx500M \
	-Dsparc.user.password=[ICART PASSWORD] \
	-Dsparc.user.password=[ICART ADMIN PASSWORD] \
	-Dsparc.url=[URL] \
	-Dsparc.fulfillment.url=[Fulfillment URL] \
	-jar fitnesse-standalone.jar -p 8080

```
3. Replace [USERNAME/PASSWORD] placeholders with the relevant values.
4. Run the command. Open a web browser and navigate to [http://localhost:8080/](http://localhost:8080/)

## Helpful references:
Basic markup: http://www.fitnesse.org/FitNesse.UserGuide.FitNesseWiki.MarkupLanguageReference  
Browser test commands: http://localhost:8080/HsacExamples.SlimTests.BrowserTests  
Symbols: http://localhost:8080/FitNesse.FullReferenceGuide.UserGuide.WritingAcceptanceTests.SliM.SymbolsInTables  
HTML selectors: http://localhost:8080/HsacExamples.SlimTests.BrowserTests.TechnicalSelectors
