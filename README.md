# WABDevNotes
Web AppBuilder for ArcGIS Development Notes

## Debugging the settings code for a custom widget
Use the following link pattern to debug the initial settings popup for a custom WAB widget https://localhost:3344/webappbuilder/?id=stemapp

## Debugging the widget itself
Use the following url pattern to debug a custom WAB widget without creating a new application
https://localhost:3344/webappviewer/?config=configs/config.json

## WebAppBuilder API Reference
https://developers.arcgis.com/web-appbuilder/guide/
Classes:
https://developers.arcgis.com/web-appbuilder/api-reference/widgetmanager.htm

## Dojo Widget LifeCycle
https://dojotoolkit.org/reference-guide/1.7/dijit/_WidgetBase.html

## WebAppBuilder Widget LifeCycle
Auto Implemented functions etc.
https://developers.arcgis.com/web-appbuilder/guide/widget-life-cycle.htm

## SVG Icons
https://esri.github.io/calcite-ui-icons/

## Best Practices
- https://gis.utah.gov/best-practices-for-building-web-appbuilder-widgets/
- https://github.com/agrc/wfrc-wab-widgets#add-a-polyfill-for-older-browsers
- https://github.com/Esri/generator-esri-appbuilder-js
- https://github.com/gbochenek/wab-test-example

## Clone ESRI objects
- https://community.esri.com/thread/180964
- var jsonGraphic = graphic.toJson(); var newGraphic = new Graphic(jsonGraphic); // instead of cloning graphics if already on screen

## Cool Vizualisations
https://ekenes.github.io/conferences/uc-2019/2d-viz/demos/sm-sliders/

## App Authentication
- https://medium.com/geographit/authentication-and-authorization-with-arcgis-online-oauth-2-0-10994e975743
- https://developers.arcgis.com/documentation/core-concepts/security-and-authentication/

#SymbolPicker
https://community.esri.com/thread/160310

## Storage / Token Authorisation
Portal uses Session Storage - access token will persist as long as the browser instance, such as Chrome is open. It will persist through refreshes and page reloads, however, when Chrome is shut down - the session ends and the user will have to login again.

## Authorise apps
https://{portal}/portal/sharing/oauth2/authorize?client_id={appid}&response_type=token&state={"portalUrl":"*{portal}/portal"}&expiration=20160&redirect_uri={redirect link to app or data}
- https://developers.arcgis.com/documentation/core-concepts/security-and-authentication/mobile-and-native-user-logins/#authorization-example
- https://medium.com/geographit/authentication-and-authorization-with-arcgis-online-oauth-2-0-10994e975743




