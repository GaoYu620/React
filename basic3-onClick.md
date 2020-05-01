# Pass data between files

###App.js

                import React, { Component } from 'react';
                import './App.css';
                import Person from './Person/Person';

                class App extends Component {
                render() {
                    return (
                    <div className="App">
                        <Person name = "Gao Yu" age = "18">My hobbies:racing</Person>
                        <Person name = "Mike" age = "19"></Person>
                        <Person name = "Marry" age = "20"></Person>

                    </div>
                    );
                }
                }

                export default App;



##Person.js
                import React from 'react';

                const person = (preps) => {
                    return (
                        <div>
                            <p>My name is {preps.name}, I am {preps.age} years old.</p>
                            <p>{preps.children}</p>
                        </div>
                    
                    
                    )
                }


                export default person;