# Mahesh Tirumalasetti 

### Munnar

**Munnar**, nestled in the lush Western Ghats of Kerala, India, is a **picturesque hill station** renowned for its breathtaking beauty. This idyllic destination is characterized by rolling **tea plantations**, misty mountains, and pristine lakes, making it a haven for nature lovers and tranquility seekers. Visitors can explore its tea estates, trek through the verdant hills, and relish the cool, crisp air. Munnar's pleasant climate and scenic landscapes make it a perfect retreat for those seeking respite from the hustle and bustle of city life.

---
###  Three activities that I can do at Munnar
---

1. Visit Tea Museums

2. Tea Plantation Tour

3. Trekking

4. Boating in Mattupetty Dam

5. Wildlife Safari

---
### List of dishes Munnar offers
---

* Munnar Tea

* Appam with Stew

* Kerala Sadya

* Puttu and Kadala Curry

**[Mahesh MyStats Demo](MyStats.md)**
**[Image](MaheshPic.jpg)**

---
# Sporting Choices for All Ages

"Sporting Choices for All Ages" presents a diverse array of physical activities suitable for individuals of any age group. Whether you're a child, a young adult, in your prime, or a senior, staying active is essential for a healthy lifestyle. In this guide, we'll explore a range of sports and fitness options tailored to different age brackets, ensuring that everyone can find an enjoyable way to maintain their well-being and engage in the world of sports

|Sport name|Sport recommendation reason|In a week average time spend on a Sport|
|:--------:|:-------------------------:|:-------------------------------------:|
|Swimming      | full-body workout that's easy on the joints. It's a life skill and a great way to beat the heat during the summer months.|3-4
|Soccer        | Ideal for kids and adults alike, soccer promotes cardiovascular fitness, teamwork, and coordination.|5-6 |
|Tennis        | A great choice for adults and teenagers, tennis improves agility, hand-eye coordination, and cardiovascular health.|3-4 |
|Martial Arts  | Martial arts like karate, taekwondo, or judo offer self-defense skills, discipline, and physical fitness.|6-7 |
|Golf          | A sport that can be enjoyed by seniors and those looking for a more leisurely activity, golf provides gentle exercise, social interaction, and an opportunity to enjoy the outdoors.| 5-6 |

---
# Pithy Quotes
> "Problems are common, but attitude makes the difference." By *APJ Abdul Kalam*

> "Everything is easy when you are busy. But nothing is easy when you are lazy." By *Swami Vivekananda*

> "Persistence is very important. You should not give up unless you are forced to give up." By *Elon Musk*

---
# Code Fencing- Track Window Resizes through Google Analytics

[Stack Quick Link](https://www.zdnet.com/education/computers-tech/what-is-stack-overflow/)

```

(function() {
  var resizeTimer;
  
  // Assuming we have jQuery present
  $( window ).on( "resize", function() {
    
    // Use resizeTimer to throttle the resize handler
    clearTimeout( resizeTimer );
    resizeTimer = setTimeout(function() {

     /* Send the event to Google Analytics
      *
      * https://developers.google.com/analytics/devguides/collection/gajs/methods/gaJSApiEventTracking
      * _trackEvent(category, action, opt_label, opt_value, opt_noninteraction)   
      */
      var $window = $( window );
      _gaq.push( [ "_trackEvent", "User Actions", "Browser Resize", $window.width() + " x " + $window.height() ] );
    }, 1000);
  });
})();

```

[Quick Link](https://css-tricks.com/snippets/jquery/track-window-resizes-through-google-analytics/)

















