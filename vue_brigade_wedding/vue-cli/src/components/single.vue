<template>
  <div>
    <base-top></base-top>
    <div class="single">
      <div class="container">
        <div class="agileits-single-img">
          <img src="static/picture/s1.jpg" alt />

          <h4>Suspendisse ornare vitae ex nec aliquam. Nunc et massa ut purus porta euismod quis eu erat. Nam ornare faucibus elit sed tempor. Quisque iaculis odio nibh, et auctor tellus rhoncus vel.</h4>
          <div class="agileinfo-single-icons">
            <ul>
              <li>
                <a href="#">
                  <i class="fa fa-user" aria-hidden="true"></i>
                  <span>Admin</span>
                </a>
              </li>
              <li>
                <i class="fa fa-calendar" aria-hidden="true"></i>
                <span>04.Nov.2015</span>
              </li>
              <li>
                <a href="#">
                  <i class="fa fa-comments-o" aria-hidden="true"></i>
                  <span>20 Comments</span>
                </a>
              </li>
              <li>
                <a href="#">
                  <i class="fa fa-heart" aria-hidden="true"></i>
                  <span>300 Likes</span>
                </a>
              </li>
            </ul>
          </div>
          <p>Vestibulum commodo posuere ipsum in elementum. Proin id nibh dictum, ornare purus quis, ullamcorper lectus. Nullam bibendum, dui eu ornare hendrerit, turpis odio tempor nulla, id tempus neque erat finibus risus. Nullam accumsan ipsum at nunc molestie, at pretium ipsum dignissim. Nullam lorem ligula, gravida sit amet tincidunt id, porta non turpis. Vestibulum tincidunt at lectus et egestas. Sed facilisis tempor tellus eget feugiat. Praesent ut est vel metus consequat consequat. Etiam interdum egestas posuere. Quisque at mi eget lorem malesuada ornare non non quam.</p>
        </div>

        <!-- comments -->
        <div class="agileits_three_comments">
          <h3>Comments</h3>
          <div class="agileits_three_comment_grid">
            <div class="agileits_tom">
              <img src="static/picture/t2.jpg" alt=" " class="img-responsive" />
            </div>
            <div class="agileits_tom_right">
              <div class="hardy">
                <h4>David Son</h4>
                <p>21 June 2016</p>
              </div>
              <div class="reply">
                <a href="#">Reply</a>
              </div>
              <div class="clearfix"></div>
              <p class="lorem">
                There are many variations of passages of Lorem Ipsum available,
                but the majority have suffered alteration in some form, by injected humour,
                or randomised words which don't.
              </p>
            </div>
            <div class="clearfix"></div>
          </div>
          <div class="agileits_three_comment_grid agileits_three_comment_grid1">
            <div class="agileits_tom">
              <img src="static/picture/t3.jpg" alt=" " class="img-responsive" />
            </div>
            <div class="agileits_tom_right">
              <div class="hardy">
                <h4>Shane Watson</h4>
                <p>21 June 2016</p>
              </div>
              <div class="reply">
                <a href="#">Reply</a>
              </div>
              <div class="clearfix"></div>
              <p class="lorem">
                There are many variations of passages of Lorem Ipsum available,
                but the majority have suffered alteration in some form, by injected humour,
                or randomised words which don't.
              </p>
            </div>
            <div class="clearfix"></div>
          </div>
          <div class="agileits_three_comment_grid">
            <div class="agileits_tom">
              <img src="static/picture/t4.jpg" alt=" " class="img-responsive" />
            </div>
            <div class="agileits_tom_right">
              <div class="hardy">
                <h4>Steve Smith</h4>
                <p>21 June 2016</p>
              </div>
              <div class="reply">
                <a href="#">Reply</a>
              </div>
              <div class="clearfix"></div>
              <p class="lorem">
                There are many variations of passages of lorem ipsum available,
                but the majority have suffered alteration in some form, by injected humour,
                or randomised words which don't.
              </p>
            </div>
            <div class="clearfix"></div>
          </div>
        </div>
        <!-- //comments -->
        <!-- leave-comments -->
        <div class="w3_leave_comment">
          <h3>Leave your comment</h3>
          <form action="#" method="post">
            <input
              type="text"
              name="Name"
              value="Name"
              onfocus="this.value = '';"
              onblur="if (this.value == '') {this.value = 'Name';}"
              required
            />
            <input
              type="email"
              name="Email"
              value="Email"
              onfocus="this.value = '';"
              onblur="if (this.value == '') {this.value = 'Email';}"
              required
            />
            <input
              type="text"
              name="Phone"
              value="Phone"
              onfocus="this.value = '';"
              onblur="if (this.value == '') {this.value = 'Phone';}"
              required
            />
            <textarea
              name="Message"
              onfocus="this.value = '';"
              onblur="if (this.value == '') {this.value = 'Message...';}"
              required
            >Message...</textarea>
            <input type="submit" value="Send" />
          </form>
        </div>
        <!-- //leave-comments -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style scoped>
</style>
