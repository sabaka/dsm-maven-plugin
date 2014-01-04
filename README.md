dsm-maven-plugin [![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/sevntu-checkstyle/dsm-maven-plugin/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

=================

Maven plugin to create HTML report to show dependecies in DSM view.


How to use plugin:

Add <reporting> section to your pom.xml and <plugin> inside it.

For example:

    <reporting>
    
        <plugins>
            <plugin>
                <groupId>org.sevntu</groupId>
                <artifactId>dsm-maven-plugin</artifactId>
                <version>2.1</version>
            </plugin>

            <!--  other reportin plugins  -->

        </plugins>

    </reporting>
    
Run mvn site. Enjoy :)