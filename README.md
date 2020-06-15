# owl-carousel-2-beta-jump-to-a-specific-slide
//working example
var gotoindex = $(this).find('.item').data('index');
owl.trigger('to.owl.carousel', [gotoindex, 200]);
