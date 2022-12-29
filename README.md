If hour is between 12AM (0) to 1PM (13) -> Good Morning
 Else if hour is between 1PM(13) to 5PM (17) -> Good Afternoon
 Else hour is between 5PM (17) to 12AM (0) -> Good Evening
let hour =19
if(hour >=0 && hour <=13 )
{
    console.log("GUDMORNING")
}
else if(hour >=13 && hour <=17)
{
    console.log("gudafternoon")
}
else
{
    console.log("GUDEVENING")
}
