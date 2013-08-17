
#### 一 良好的表达式

     1 unless replace if !
     eg. unless tweets.empty
           puts "Timeline"
           puts tweets
         end
     eg. games = ["Super Mario Bros.", "Contra", "Metroid", "Mega Man 2"]
         puts "Games in your vast collection: #{games.count}" unless games.empty?
      
     2 if else replace unless with else
      
     3 nil is false - if replace if !=nil
      
     4 only nil is false - ""/0/[] treated as "ture"!
     
     5 inline conditionals
     eg. puts "Game #{search} found." if matched_games.include?(search)
      
     6 short-circuit - "and"/"assignment"/"or"/"evaluation"
     eg.tweets ||= '' 
      
     7 conditional return values
      
     8 case statement value
     
     9 case - ranges
      
     10 case - regexps
      
     11 case - when/then
