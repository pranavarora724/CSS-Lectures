Love Babbar's Project

**MOST IMP**
Don't set any height of the outermost grid container
Let it be decided automatically (will cause issuss in responsiveness)
*************

grid-template-columns: repeat(auto-fit,minmax(200px,250px));
justify-content: center;


Will make sure that cards have min width 200px and max width 250px



**Make IMAGE CENTER

.card_image_container{
    height: 55%;
    overflow: hidden;
    position: relative;                  //Make Parent Hidden
}
.card_image{
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
    position: absolute;              //Make Child Absolute
}


**We Hover on Card  BUT Card-image Gets scaled

.card:hover .card_image{
transform: scale(1.05);
transition-duration: 200ms;
}