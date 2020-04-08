1.adding pitest plugin in .pom file

            <plugin>
                <groupId>org.pitest</groupId>
                <artifactId>pitest-maven</artifactId>
                <version>1.4.3</version>
                <executions>
                    <execution>
                        <id>pit-report</id>
                        <phase>test</phase>
                        <goals>
                            <goal>mutationCoverage</goal>
                        </goals>
                    </execution>
                </executions>
            </plugin>
2.running mvn clean

3.running mvn test
