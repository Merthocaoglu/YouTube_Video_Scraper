# YouTube_Video_Scraper
This code enables you to scrape YouTube video's datas (video url , video upload date , video title , video views)
HOW IT WORKS???
First of all you need to copy the YouTube channels url 'https://www.youtube.com/@DMAXTurkiye/videos' then you need to paste this url to [driver.get('...')] 
when you run this code shell you will see a chrome tab in front of you based on your screen resolation you will see ... number amount videos
as you can see dmax Turkiye channel have over 1.5 k videos in order to get this videos all together we must use this two (.send_keys(Keys.END)), (for _ in range(60):)
if you are not scraping over the 1.5 k videos you can lower the range number it will save you some time . 
