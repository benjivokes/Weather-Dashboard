# Weather Dashboard







#### Functionality 

This is a weather dashboard that states current weather and a 5 day forecast for city searched.



# Base HTML Structure
        <label class="option"><input type="radio" </div>
              <div class="col-md-9 mt-3" id="searchResults">
                <div class="row weather-conditions">
                 <div class="col-md-12">
                  <div class="card">
                    <div class="card-body" id="currentWeather">
                     <h3 class="card-title">
                      <span id="currentCity"></span>
                       <span id="todaysDate"></span>
                        <img src="" alt="" id="currentWeatherIcon"></h3>
                        <ul class="card-text current-weather-conditions">
                        <li>Temperature: <span id="todaysTemp"></span>&degF</li>
                        <li>Humidity: <span id="todaysHumidity"></span>%</li>
                        <li>Wind Speed: <span id="todaysWindSpeed"></span>MPH</li>
                        <li>UV Index:<span class="border d-inline-block rounded px-2 py-1" id="todaysUVIndex">
                     </span>
                    </li>
                   </ul>
                  </div>
                 </div>
                </div>
             </div>

