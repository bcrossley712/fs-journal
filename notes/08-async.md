# MVC

READ THE API DOCS!!!!!


//SECTION Asynchronous Code
API - Application program interface
Asynchronous - tell the code to wait for something before proceeding to the next step.
  async - await

Network tab - Fetch/XHR

CRUD - create read update delete/destroy

All methods in the Controller should now have a try/catch
  Catches should have minimum :
    catch(error){
      console.error(error)
      Pop.toast(error.message, 'error')
    }

//  LOG THE RES!!! // (short for response)
const res = await axios.get("https...")
console.log(response.data)

//SECTION Axios
  AxiosService
    export const api = axios.create({
      baseURL: '#baseApiUrl',
      timeout: 8000
    })

//SECTION CRUD
  Create - post
  Read - get
  Update - put
  Delete - delete

