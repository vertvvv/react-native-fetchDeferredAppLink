# react-native-fetchDeferredAppLink

   <B>Usage</B>
   <BR>
   const { FBAppLink } = NativeModules;
  
    FBAppLink.get().then(url => {
    
      console.log(url);

      //or console.log(queryString.parseUrl(url)) to get an object with params;
      //npm i query-string
      //yarn add query-string
    });
