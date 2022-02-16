# MVC

Model View Controller (Service)


View(DOM)
The controllers job is to update the DOM
Service is the business logic. Where the majority of the code will happen.
Model is the blueprint or the data structure
All information will be stored in the AppState(ProxyState)

BCW Tool - bcw create
mvc

Getter functions create fake properties that run like functions; they must return a function

//SECTION Controller
export - export class NameController{

          }


//SECTION Services
start with a singleton - class NameService{

                          }
                          export const nameService = new NameService()


//SECTION Model


//SECTION State (AppState/ProxyState)
You have to go through the proxyState to get information from the AppState
