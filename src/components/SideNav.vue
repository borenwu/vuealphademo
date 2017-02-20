<template>
  <aside id="slide-out" class="side-nav white fixed">
    <div class="side-nav-wrapper">
      <div class="sidebar-profile">
        <div class="sidebar-profile-image">
          <img src="static/images/profile-image.png" class="circle" alt="">
        </div>
        <div class="sidebar-profile-info">
          <a href="javascript:void(0);" class="account-settings-link">
            <p>David Doe</p>
            <span>david@gmail.com<i class="material-icons right">arrow_drop_down</i></span>
          </a>
        </div>
      </div>
      <div class="sidebar-account-settings">
        <ul>
          <li class="no-padding">
            <a class="waves-effect waves-grey"><i class="material-icons">mail_outline</i>Inbox</a>
          </li>
          <li class="no-padding">
            <a class="waves-effect waves-grey"><i class="material-icons">star_border</i>Starred<span class="new badge">18</span></a>
          </li>
          <li class="no-padding">
            <a class="waves-effect waves-grey"><i class="material-icons">done</i>Sent Mail</a>
          </li>
          <li class="no-padding">
            <a class="waves-effect waves-grey"><i class="material-icons">history</i>History<span
              class="new grey lighten-1 badge">3 new</span></a>
          </li>
          <li class="divider"></li>
          <li class="no-padding">
            <a class="waves-effect waves-grey"><i class="material-icons">exit_to_app</i>Sign Out</a>
          </li>
        </ul>
      </div>

      <ul class="sidebar-menu collapsible collapsible-accordion" data-collapsible="accordion">
        <li class="no-padding active">
          <router-link class="cwaves-effect waves-grey active" to="/home">
            <i class="material-icons">dashboard</i> 主页
          </router-link>
        </li>

        <li class="no-padding">
          <router-link class="collapsible-header waves-effect waves-grey" to="/order">
            <i class="material-icons">apps</i>
            订单
            <i class="nav-drop-icon material-icons">keyboard_arrow_right</i>
          </router-link>
          <!--<a class="collapsible-header waves-effect waves-grey">-->
            <!--<i class="material-icons">apps</i>-->
            <!--Apps-->
            <!--<i class="nav-drop-icon material-icons">keyboard_arrow_right</i>-->
          <!--</a>-->
          <div class="collapsible-body">
            <ul>
              <li><a href="mailbox.html">Mailbox</a></li>
              <li><a href="search.html">Search</a></li>
              <li><a href="todo.html">Todo</a></li>
            </ul>
          </div>
        </li>

        <li class="no-padding">
          <router-link class="collapsible-header waves-effect waves-grey" to="/work">
            <i class="material-icons">code</i>
            工作
            <i class="nav-drop-icon material-icons">keyboard_arrow_right</i>
          </router-link>
          <div class="collapsible-body">
            <ul>
              <li><a href="ui-accordions.html">Accordion</a></li>
              <li><a href="ui-badges.html">Badges</a></li>
              <li><a href="ui-buttons.html">Buttons</a></li>
              <li><a href="ui-typography.html">Typography</a></li>
              <li><a href="ui-cards.html">Cards</a></li>
              <li><a href="ui-carousel.html">Carousel</a></li>
              <li><a href="ui-chips.html">Chips</a></li>
              <li><a href="ui-color.html">Color</a></li>
              <li><a href="ui-collections.html">Collections</a></li>
              <li><a href="ui-dropdown.html">Dropdown</a></li>
              <li><a href="ui-dialogs.html">Dialogs</a></li>
              <li><a href="ui-grid.html">Grid</a></li>
              <li><a href="ui-helpers.html">Helpers</a></li>
              <li><a href="ui-modals.html">Modals</a></li>
              <li><a href="ui-media.html">Media</a></li>
              <li><a href="ui-icons.html">Icons</a></li>
              <li><a href="ui-parallax.html">Parallax</a></li>
              <li><a href="ui-preloader.html">Preloader</a></li>
              <li><a href="ui-shadow.html">Shadow</a></li>
              <li><a href="ui-tabs.html">Tabs</a></li>
              <li><a href="ui-waves.html">Waves</a></li>
            </ul>
          </div>
        </li>

        <li class="no-padding">
          <router-link class="collapsible-header waves-effect waves-grey" to="/warehouse">
            <i class="material-icons">store</i>
            仓库
            <i class="nav-drop-icon material-icons">keyboard_arrow_right</i>
          </router-link>
          <div class="collapsible-body">
            <ul>
              <li><a href="miscellaneous-sweetalert.html">Sweet Alert</a>
              <li><a href="miscellaneous-code-editor.html">Code Editor</a>
              <li><a href="miscellaneous-nestable.html">Nestable List</a>
              <li><a href="miscellaneous-masonry.html">Masonry</a>
              <li><a href="miscellaneous-idle-timer.html">Idle Timer</a>
            </ul>
          </div>
        </li>

        <li class="no-padding">
          <router-link class="collapsible-header waves-effect waves-grey" to="/finance">
            <i class="material-icons">desktop_windows</i>
            财务
            <i class="nav-drop-icon material-icons">keyboard_arrow_right</i>
          </router-link>
          <div class="collapsible-body">
            <ul>
              <li><a href="layout-blank.html">Blank Page</a></li>
              <li><a href="layout-boxed.html">Boxed Layout</a></li>
              <li><a href="layout-hidden-sidebar.html">Hidden Sidebar</a></li>
              <li><a href="layout-right-sidebar.html">Right Sidebar</a></li>
            </ul>
          </div>
        </li>

      </ul>
      <div class="footer">
        <p class="copyright">Steelcoders ©</p>
        <a href="#!">Privacy</a> &amp; <a href="#!">Terms</a>
      </div>
    </div>
  </aside>
</template>

<style>

</style>

<script>

    export default{
        data(){
            return{
                msg:'hello side nav'
            }
        },
        components:{

        }
    }
</script>
