# wordcount-java

Word count with Java

```java
// Main logic

        File file = new File("how_to_live_on_24_hours_a_day.txt");
        Scanner scanner = new Scanner(file);

        int words = 0;
        while(scanner.hasNextLine()) {
            String line = scanner.nextLine();
            words += line.split(" ").length;

        }
```
