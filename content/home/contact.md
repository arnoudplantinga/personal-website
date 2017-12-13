+++
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.

date = "2016-04-20T00:00:00"
draft = false

title = "Contact"
subtitle = ""
widget = "custom"

# Order that this section will appear in.
weight = 60

+++

<div class="col-xs-12 col-md-8">
    <ul class="fa-ul" itemscope="">
      <li>
        <i class="fa-li fa fa-envelope fa-2x" aria-hidden="true"></i>
        <span id="person-email" itemprop="email"><a href="mailto:a.plantinga@tilburguniversity.edu">a.plantinga@tilburguniversity.edu</a></span>
      </li>
      <li>
        <i class="fa-li fa fa-clock-o fa-2x" aria-hidden="true"></i>
        <span id="person-meeting" itemprop="meeting"><a href="meeting">Schedule a meeting</a></span>
      </li>
      <li>
        <i class="fa-li fa fa-map-marker fa-2x" aria-hidden="true"></i>
        <span id="person-address" itemprop="address"><a href="https://goo.gl/maps/rLcos5srbDC2">Room S 416, Tilburg University, The Netherlands</a></span>
      </li>
      <li>
        <i class="fa-li fa fa-phone fa-2x" aria-hidden="true"></i>
        <span id="person-telephone" itemprop="telephone"><a href="tel:013 466 3516">013 466 3516</a></span>
      </li>
    </ul>
  </div>
