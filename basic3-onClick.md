   # Pass data between files


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

 sss