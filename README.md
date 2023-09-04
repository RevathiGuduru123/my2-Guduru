# my2-Guduru
# Guduru Revathi
###### Goa
Goa holds a __special place in my heart__. It's __pristine beaches__ ,warm and beneath my feet makes me feel happy and peaceful.
-----
# vacation spot
1. Enjoying the food
2. Having fun 
3. Challenges

* Bebinca
* rice and fish curry
* sea food 

Here is the MyStats link
[statlink](https://github.com/RevathiGuduru123/my2-Guduru/blob/main/MyStats.md)

# sports 
In the below table we will get to know about the sports with the reason to recommend to play the listed sports and the hours to spend on those sports in our daily life

|   Sport    |   Reason           | Hours spending |
|  ---       |   ----             |    ----        |
| Badminton  |  Physical exercise |    one         |
| BasketBall |  Team Work         |    two         |
| olleyBall  |  Stress Relief     |    one         |
| Tennis     |  Mental Focus      |    two         |

# quotes
> If I have seen further it is by standing on the shoulders of giants - *Isaac Newton*

> Somewhere,something is incredible is waiting to be known by - *Carl Sagan*

-------------------------------------------------------
# code snippet
>Add the correct number of commas 

[stackoverflowlink](https://stackoverflow.com/questions/26713855/add-the-correct-number-of-commas)


the_category with Excludes 
```
function exclude_post_categories($excl='', $spacer=' ') {
  $categories = get_the_category(get_the_ID());
  if (!empty($categories)) {
    $exclude = $excl;
    $exclude = explode(",", $exclude);
    $thecount = count(get_the_category()) - count($exclude);
    foreach ($categories as $cat) {
      $html = '';
      if (!in_array($cat->cat_ID, $exclude)) {
        $html .= '<a href="' . get_category_link($cat->cat_ID) . '" ';
        $html .= 'title="' . $cat->cat_name . '">' . $cat->cat_name . '</a>';
        if ($thecount > 0) {
          $html .= $spacer;
        }
        $thecount--;
        echo $html;
      }
    }
  }
}
```
Here is the link for the code snippet
[referencelink](https://css-tricks.com/snippets/wordpress/the_category-excludes/)





