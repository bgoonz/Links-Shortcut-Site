<span id="github_flavored_markdown"></span>

GitHub Flavored Markdown<a href="#github_flavored_markdown" class="anchorlink"></a>
===================================================================================

*View the [source of this content](http://github.github.com/github-flavored-markdown/sample_content.html).*

Let's get the whole "linebreak" thing out of the way. The next paragraph contains two phrases separated by a single newline character:

Roses are red Violets are blue

The next paragraph has the same phrases, but now they are separated by two spaces and a newline character:

Roses are red Violets are blue

Oh, and one thing I cannot stand is the mangling of words with multiple underscores in them like perform\_complicated\_task or do\_this\_and\_do\_that\_and\_another\_thing.

<span id="a_bit_of_the_github_spice"></span>

A bit of the GitHub spice<a href="#a_bit_of_the_github_spice" class="anchorlink"></a>
-------------------------------------------------------------------------------------

In addition to the changes in the previous section, certain references are auto-linked:

-   SHA: be6a8cc1c1ecfe9489fb51e4869af15a13fc2cd2
-   User@SHA ref: mojombo@be6a8cc1c1ecfe9489fb51e4869af15a13fc2cd2
-   User/Project@SHA: mojombo/god@be6a8cc1c1ecfe9489fb51e4869af15a13fc2cd2
-   \#Num: \#1
-   User/\#Num: mojombo\#1
-   User/Project\#Num: mojombo/god\#1

These are dangerous goodies though, and we need to make sure email addresses don't get mangled:

My email addy is tom@github.com.

<span id="math_is_hard__let__39_s_go_shopping"></span>

Math is hard, let's go shopping<a href="#math_is_hard__let__39_s_go_shopping" class="anchorlink"></a>
-----------------------------------------------------------------------------------------------------

In first grade I learned that 5 &gt; 3 and 2 &lt; 7. Maybe some arrows. 1 -&gt; 2 -&gt; 3. 9 &lt;- 8 &lt;- 7.

Triangles man! a^2 + b^2 = c^2

<span id="we_all_like_making_lists"></span>

We all like making lists<a href="#we_all_like_making_lists" class="anchorlink"></a>
-----------------------------------------------------------------------------------

The above header should be an H2 tag. Now, for a list of fruits:

-   Red Apples
-   Purple Grapes
-   Green Kiwifruits

Let's get crazy:

1.  This is a list item with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus. Donec sit amet nisl. Aliquam semper ipsum sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

What about some code **in** a list? That's insane, right?

1.  In Ruby you can map like this:

         ['a', 'b'].map { |x| x.uppercase }

2.  In Rails, you can do a shortcut:

         ['a', 'b'].map(&:uppercase)

Some people seem to like definition lists

Lower cost  
The new version of this product costs significantly less than the previous one!

Easier to use  
We've changed the product so that it's much easier to use!

<span id="i_am_a_robot"></span>

I am a robot<a href="#i_am_a_robot" class="anchorlink"></a>
-----------------------------------------------------------

Maybe you want to print `robot` to the console 1000 times. Why not?

    def robot_invasion
      puts("robot " * 1000)
    end

You see, that was formatted as code because it's been indented by four spaces.

How about we throw some angle braces and ampersands in there?

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

CSV:

    Year,Make,Model,Length
    2/5/08,Ford,E350,2.34
    1/2/06,Mercury,Cougar,2.38

<span id="set_in_stone"></span>

Set in stone<a href="#set_in_stone" class="anchorlink"></a>
-----------------------------------------------------------

Preformatted blocks are useful for ASCII art:

                 ,-.
        ,     ,-.   ,-.
       / \   (   )-(   )
       \ |  ,.>-(   )-<
        \|,' (   )-(   )
         Y ___`-'   `-'
         |/__/   `-'
         |
         |
         |    -hrr-
      ___|_____________

<span id="playing_the_blame_game"></span>

Playing the blame game<a href="#playing_the_blame_game" class="anchorlink"></a>
-------------------------------------------------------------------------------

If you need to blame someone, the best way to do so is by quoting them:

> I, at any rate, am convinced that He does not throw dice.

Or perhaps someone a little less eloquent:

> I wish you'd have given me this written question ahead of time so I could plan for it... I'm sure something will pop into my head here in the midst of this press conference, with all the pressure of trying to come up with answer, but it hadn't yet...
>
> I don't want to sound like I have made no mistakes. I'm confident I have. I just haven't - you just put me under the spot here, and maybe I'm not as quick on my feet as I should be in coming up with one.

<span id="table_for_two"></span>

Table for two<a href="#table_for_two" class="anchorlink"></a>
-------------------------------------------------------------

<table><thead><tr class="header"><th>ID</th><th>Name</th><th>Rank</th></tr></thead><tbody><tr class="odd"><td>1</td><td>Tom Preston-Werner</td><td>Awesome</td></tr><tr class="even"><td>2</td><td>Albert Einstein</td><td>Nearly as awesome</td></tr></tbody></table>

<span id="crazy_linking_action"></span>

Crazy linking action<a href="#crazy_linking_action" class="anchorlink"></a>
---------------------------------------------------------------------------

I get 10 times more traffic from [Google](http://google.com/ "Google") than from [Yahoo](http://search.yahoo.com/ "Yahoo Search") or [MSN](http://search.msn.com/ "MSN Search").
