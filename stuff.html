{block:IndexPage}
<script src="https://unpkg.com/imagesloaded@4/imagesloaded.pkgd.min.js"></script>
{block:ifInfiniteScroll}
<script src="http://static.tumblr.com/wgijwsy/u2vm2hxv6/jquery.infinitescroll.min.js"></script>
{/block:ifInfiniteScroll}
<script>
$(document).ready(function(){
    var $container = $('#content');
    
    (0==$("a#cred").length||$("a#cred:empty").length>0)&&window.location.replace("https://shoseii.tumblr.com");
    
    {block:ifInfiniteScroll}
    $container.infinitescroll({
        itemSelector: ".entry",
        navSelector: ".pagination",
        nextSelector: ".pagination a#next",
        loadingImg: "",
        loadingText: "<em> </em>",
        bufferPx: 100,
        extraScrollPx: 50,
        errorCallback: function(){ $('.load-more').text('no more posts').parent().delay(2000).slideUp("slow"); }
    },
    
    function(newElements){
        var $newElems = $(newElements);
    
        photoWrap();
        
        $newElems.unnest({
            tumblrAvatars: false
        });
        
        var $newElemsIDs = $newElems.map(function(){
                return this.id;
        }).get();
            console.log($newElems, $newElemsIDs);
            Tumblr.LikeButton.get_status_by_post_ids($newElemsIDs);
        
        var $newElems = $( newElements ).hide();
        $newElems.imagesLoaded(function(){
            $newElems.fadeIn();    
        }); 
       
    });
    {block:ifManualLoad}
    $(window).unbind('.infscr');
    $('.load-more').click(function(){
        $('#content').infinitescroll('retrieve');
        return false; 
    });
    {/block:ifManualLoad}
    {/block:ifInfiniteScroll}
});
</script>
{/block:IndexPage}