# Investigating the language used when reporting on men's and women's professional football (soccer)

## TL:DR
Match reports from both men's and women's professional matches were scraped from BBCSport and analysed using NLP techniques to look for biasses in the language used.

## Background
Women's professional sport has for a long time taken a back seat to the male equivalent and - at least in the UK - the same goes for football.  Indeed the Football Association (FA) banned women's football in 1921 seeing it as unladylike, a ban that would stand until around 1971 following pressure from UEFA.  However interest - and with it, sponsorship, investment and coverage - in women's football in the UK has greatly increased over the last 5-10 years.  In part this is due to recent successes of the Lionesses - the England women's team - and resulted in what was described as a landmark deal by the Women's FA.  The deal led to Sky Sports and BBC sharing 57 Women's Super League (WSL) games per season and was worth around £8million a year.
While this is huge progress, it still pales in significance to the levels of coverage and investment in the men's game.  The equivalent league, The Premier League (EPL) is by far the most lucrative domestic football TV rights deal, screening 200 matches per season across 3 different broadcasters at a reported £1.6bn per season.

The purpose of this project was to investigate if there are any subconscious biases in the manner in which the two sports are reported on.  In particular, can Natural Language Processing (NLP) show any patterns in the way the two sports are reported on and the language used that may be further holding back the growth of the women's game.

## Methodology - Data Collection
The BBC sport website was chosen specifically because of it's popularity.  According to BBC's own reporting over 20million people use BBCSport website every week.  As a free content website that does not specialise in a particular club (certain websites are dedicated to coverage of specific clubs or leagues) it is less likely to show bias and has a large catalogue of articles and match reports on profesisonal football from both the men's and women's game. 
 
