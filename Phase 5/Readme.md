ANIMATION lecture

  animation-name: slidein;                      //name
  animation-duration: 3s;
  animation-iteration-count: infinite;
  animation-direction: alternate;             //Start hoke it will repeat agin in opposit direction

  @keyframes slidein 
  {
    from{
        top:0px;
        left:0px;
    }
    50%{                     //when animation is 50% complete
        top:0px;                    
        left:1000px;
    }
    to{
        top:0px;
        left:0px;
    }
  }


  SHADOW EFFETCS
             x-axis  y-axis blur  shadow  color
  box-shadow: 10px    10px   5px   1px   brown;

  +10px = positive x axis
  -10px = negative x axis