

            var app = new Vue({
              el: '#app',
              data: {
                counter: 0, 
                home: true,
                second: false,
                third: false,
                fourth: false,
                ref: false
              },
              methods: {
                selecthome: function(){
                  this.home === true;
                  this.second === false;
                  this.third === false;
                  this.fourth === false;
                  this.ref === false;
                }
              },
              select2: function(){
                  this.home = false
                  this.second = true
                  this.third = false
                  this.fourth = false
                  this.ref = false
                }
            })
