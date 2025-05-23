---
title: Timelines
summary: A timeline is a perfect way to visualize processes and projects, as it's easy to read and attractive for users. You can use it to give an overview of events, present an agenda or point out important points in time.
description: Visualize events and processes clearly.
---

## Timeline

The available timeline design is composed of many components that will help you visualize a process or show an outline of events. Thanks to the possibility of adding icons, avatars and links and the way of presenting the elements of content, your timeline will be clear for users and will make your website or app more attractive.

{% capture html -%}
<ul class="timeline">
  <li class="timeline-event">
    <div class="timeline-event-icon bg-twitter-lt">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <path
          d="M22 4.01c-1 .49 -1.98 .689 -3 .99c-1.121 -1.265 -2.783 -1.335 -4.38 -.737s-2.643 2.06 -2.62 3.737v1c-3.245 .083 -6.135 -1.395 -8 -4c0 0 -4.182 7.433 4 11c-1.872 1.247 -3.739 2.088 -6 2c3.308 1.803 6.913 2.423 10.034 1.517c3.58 -1.04 6.522 -3.723 7.651 -7.742a13.84 13.84 0 0 0 .497 -3.753c-.002 -.249 1.51 -2.772 1.818 -4.013z"
        />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">10 hrs ago</div>
        <h4>+1150 Followers</h4>
        <p class="text-secondary">You’re getting more and more followers, keep it up!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <rect x="3" y="7" width="18" height="13" rx="2" />
        <path d="M8 7v-2a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v2" />
        <line x1="12" y1="12" x2="12" y2="12.01" />
        <path d="M3 13a20 20 0 0 0 18 0" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 hrs ago</div>
        <h4>+3 New Products were added!</h4>
        <p class="text-secondary">Congratulations!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <path d="M5 12l5 5l10 -10" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">1 day ago</div>
        <h4>Database backup completed!</h4>
        <p class="text-secondary">Download the <a href="#">latest backup</a>.</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon bg-facebook-lt">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <path d="M7 10v4h3v7h4v-7h3l1 -4h-4v-2a1 1 0 0 1 1 -1h3v-4h-3a5 5 0 0 0 -5 5v2h-3" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">1 day ago</div>
        <h4>+290 Page Likes</h4>
        <p class="text-secondary">This is great, keep it up!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <circle cx="9" cy="7" r="4" />
        <path d="M3 21v-2a4 4 0 0 1 4 -4h4a4 4 0 0 1 4 4v2" />
        <path d="M16 11h6m-3 -3v6" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 days ago</div>
        <h4>+3 Friend Requests</h4>
        <div class="avatar-list mt-3">
          <span class="avatar" style="background-image: url(...)">
            <span class="badge bg-success"></span>
          </span>
          <span class="avatar"> <span class="badge bg-success"></span>JL </span>
          <span class="avatar" style="background-image: url(...)">
            <span class="badge bg-success"></span>
          </span>
        </div>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <line x1="15" y1="8" x2="15.01" y2="8" />
        <rect x="4" y="4" width="16" height="16" rx="3" />
        <path d="M4 15l4 -4a3 5 0 0 1 3 0l5 5" />
        <path d="M14 14l1 -1a3 5 0 0 1 3 0l2 2" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">3 days ago</div>
        <h4>+2 New photos</h4>
        <div class="mt-3">
          <div class="row g-2">
            <div class="col-6">
              <div class="media media-2x1 rounded">
                <a class="media-content" style="background-image: url(...)"></a>
              </div>
            </div>
            <div class="col-6">
              <div class="media media-2x1 rounded">
                <a class="media-content" style="background-image: url(...)"></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <path
          d="M10.325 4.317c.426 -1.756 2.924 -1.756 3.35 0a1.724 1.724 0 0 0 2.573 1.066c1.543 -.94 3.31 .826 2.37 2.37a1.724 1.724 0 0 0 1.065 2.572c1.756 .426 1.756 2.924 0 3.35a1.724 1.724 0 0 0 -1.066 2.573c.94 1.543 -.826 3.31 -2.37 2.37a1.724 1.724 0 0 0 -2.572 1.065c-.426 1.756 -2.924 1.756 -3.35 0a1.724 1.724 0 0 0 -2.573 -1.066c-1.543 .94 -3.31 -.826 -2.37 -2.37a1.724 1.724 0 0 0 -1.065 -2.572c-1.756 -.426 -1.756 -2.924 0 -3.35a1.724 1.724 0 0 0 1.066 -2.573c-.94 -1.543 .826 -3.31 2.37 -2.37c1 .608 2.296 .07 2.572 -1.065z"
        />
        <circle cx="12" cy="12" r="3" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 weeks ago</div>
        <h4>System updated to v2.02</h4>
        <p class="text-secondary">
          Check the complete changelog at the <a href="#">activity page</a>.
        </p>
      </div>
    </div>
  </li>
</ul>
{%- endcapture %}
{% include "docs/example.html" html=html %}

```html
<ul class="timeline">
  <li class="timeline-event">
    <div class="timeline-event-icon bg-twitter-lt">
      {% include "ui/icon.html" icon="brand-twitter" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">10 hrs ago</div>
        <h4>+1150 Followers</h4>
        <p class="text-secondary">You’re getting more and more followers, keep it up!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="briefcase" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 hrs ago</div>
        <h4>+3 New Products were added!</h4>
        <p class="text-secondary">Congratulations!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="check" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">1 day ago</div>
        <h4>Database backup completed!</h4>
        <p class="text-secondary">Download the <a href="#">latest backup</a>.</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon bg-facebook-lt">
      {% include "ui/icon.html" icon="brand-facebook" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">1 day ago</div>
        <h4>+290 Page Likes</h4>
        <p class="text-secondary">This is great, keep it up!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="user-plus" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 days ago</div>
        <h4>+3 Friend Requests</h4>
        <div class="avatar-list mt-3">
          <span class="avatar" style="background-image: url(...)">
            <span class="badge bg-success"></span>
          </span>
          <span class="avatar"> <span class="badge bg-success"></span>JL </span>
          <span class="avatar" style="background-image: url(...)">
            <span class="badge bg-success"></span>
          </span>
        </div>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="photo" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">3 days ago</div>
        <h4>+2 New photos</h4>
        <div class="mt-3">
          <div class="row g-2">
            <div class="col-6">
              <div class="media media-2x1 rounded">
                <a class="media-content" style="background-image: url(...)"></a>
              </div>
            </div>
            <div class="col-6">
              <div class="media media-2x1 rounded">
                <a class="media-content" style="background-image: url(...)"></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="settings" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 weeks ago</div>
        <h4>System updated to v2.02</h4>
        <p class="text-secondary">
          Check the complete changelog at the <a href="#">activity page</a>.
        </p>
      </div>
    </div>
  </li>
</ul>
```

## Simple timeline

Use a simplified version of the timeline, if it suits your design better. You can still make use of all the available timeline components.

{% capture html -%}
<ul class="timeline timeline-simple">
  <li class="timeline-event">
    <div class="timeline-event-icon bg-twitter-lt">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <path
          d="M22 4.01c-1 .49 -1.98 .689 -3 .99c-1.121 -1.265 -2.783 -1.335 -4.38 -.737s-2.643 2.06 -2.62 3.737v1c-3.245 .083 -6.135 -1.395 -8 -4c0 0 -4.182 7.433 4 11c-1.872 1.247 -3.739 2.088 -6 2c3.308 1.803 6.913 2.423 10.034 1.517c3.58 -1.04 6.522 -3.723 7.651 -7.742a13.84 13.84 0 0 0 .497 -3.753c-.002 -.249 1.51 -2.772 1.818 -4.013z"
        />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">10 hrs ago</div>
        <h4>+1150 Followers</h4>
        <p class="text-secondary">You’re getting more and more followers, keep it up!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <rect x="3" y="7" width="18" height="13" rx="2" />
        <path d="M8 7v-2a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v2" />
        <line x1="12" y1="12" x2="12" y2="12.01" />
        <path d="M3 13a20 20 0 0 0 18 0" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 hrs ago</div>
        <h4>+3 New Products were added!</h4>
        <p class="text-secondary">Congratulations!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <path d="M5 12l5 5l10 -10" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">1 day ago</div>
        <h4>Database backup completed!</h4>
        <p class="text-secondary">Download the <a href="#">latest backup</a>.</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon bg-facebook-lt">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <path d="M7 10v4h3v7h4v-7h3l1 -4h-4v-2a1 1 0 0 1 1 -1h3v-4h-3a5 5 0 0 0 -5 5v2h-3" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">1 day ago</div>
        <h4>+290 Page Likes</h4>
        <p class="text-secondary">This is great, keep it up!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <circle cx="9" cy="7" r="4" />
        <path d="M3 21v-2a4 4 0 0 1 4 -4h4a4 4 0 0 1 4 4v2" />
        <path d="M16 11h6m-3 -3v6" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 days ago</div>
        <h4>+3 Friend Requests</h4>
        <div class="avatar-list mt-3">
          <span class="avatar" style="background-image: url(...)">
            <span class="badge bg-success"></span>
          </span>
          <span class="avatar"> <span class="badge bg-success"></span>JL </span>
          <span class="avatar" style="background-image: url(...)">
            <span class="badge bg-success"></span>
          </span>
        </div>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <line x1="15" y1="8" x2="15.01" y2="8" />
        <rect x="4" y="4" width="16" height="16" rx="3" />
        <path d="M4 15l4 -4a3 5 0 0 1 3 0l5 5" />
        <path d="M14 14l1 -1a3 5 0 0 1 3 0l2 2" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">3 days ago</div>
        <h4>+2 New photos</h4>
        <div class="mt-3">
          <div class="row g-2">
            <div class="col-6">
              <div class="media media-2x1 rounded">
                <a class="media-content" style="background-image: url(...)"></a>
              </div>
            </div>
            <div class="col-6">
              <div class="media media-2x1 rounded">
                <a class="media-content" style="background-image: url(...)"></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="icon"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        stroke-width="2"
        stroke="currentColor"
        fill="none"
        stroke-linecap="round"
        stroke-linejoin="round"
      >
        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
        <path
          d="M10.325 4.317c.426 -1.756 2.924 -1.756 3.35 0a1.724 1.724 0 0 0 2.573 1.066c1.543 -.94 3.31 .826 2.37 2.37a1.724 1.724 0 0 0 1.065 2.572c1.756 .426 1.756 2.924 0 3.35a1.724 1.724 0 0 0 -1.066 2.573c.94 1.543 -.826 3.31 -2.37 2.37a1.724 1.724 0 0 0 -2.572 1.065c-.426 1.756 -2.924 1.756 -3.35 0a1.724 1.724 0 0 0 -2.573 -1.066c-1.543 .94 -3.31 -.826 -2.37 -2.37a1.724 1.724 0 0 0 -1.065 -2.572c-1.756 -.426 -1.756 -2.924 0 -3.35a1.724 1.724 0 0 0 1.066 -2.573c-.94 -1.543 .826 -3.31 2.37 -2.37c1 .608 2.296 .07 2.572 -1.065z"
        />
        <circle cx="12" cy="12" r="3" />
      </svg>
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 weeks ago</div>
        <h4>System updated to v2.02</h4>
        <p class="text-secondary">
          Check the complete changelog at the <a href="#">activity page</a>.
        </p>
      </div>
    </div>
  </li>
</ul>
{%- endcapture %}
{% include "docs/example.html" html=html %}

```html
<ul class="timeline timeline-simple">
  <li class="timeline-event">
    <div class="timeline-event-icon bg-twitter-lt">
      {% include "ui/icon.html" icon="brand-twitter" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">10 hrs ago</div>
        <h4>+1150 Followers</h4>
        <p class="text-secondary">You’re getting more and more followers, keep it up!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="briefcase" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 hrs ago</div>
        <h4>+3 New Products were added!</h4>
        <p class="text-secondary">Congratulations!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="check" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">1 day ago</div>
        <h4>Database backup completed!</h4>
        <p class="text-secondary">Download the <a href="#">latest backup</a>.</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon bg-facebook-lt">
      {% include "ui/icon.html" icon="brand-facebook" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">1 day ago</div>
        <h4>+290 Page Likes</h4>
        <p class="text-secondary">This is great, keep it up!</p>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="user-plus" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 days ago</div>
        <h4>+3 Friend Requests</h4>
        <div class="avatar-list mt-3">
          <span class="avatar" style="background-image: url(...)">
            <span class="badge bg-success"></span>
          </span>
          <span class="avatar"> <span class="badge bg-success"></span>JL </span>
          <span class="avatar" style="background-image: url(...)">
            <span class="badge bg-success"></span>
          </span>
        </div>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="photo" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">3 days ago</div>
        <h4>+2 New photos</h4>
        <div class="mt-3">
          <div class="row g-2">
            <div class="col-6">
              <div class="media media-2x1 rounded">
                <a class="media-content" style="background-image: url(...)"></a>
              </div>
            </div>
            <div class="col-6">
              <div class="media media-2x1 rounded">
                <a class="media-content" style="background-image: url(...)"></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </li>
  <li class="timeline-event">
    <div class="timeline-event-icon">
      {% include "ui/icon.html" icon="settings" %}
    </div>
    <div class="card timeline-event-card">
      <div class="card-body">
        <div class="text-secondary float-end">2 weeks ago</div>
        <h4>System updated to v2.02</h4>
        <p class="text-secondary">
          Check the complete changelog at the <a href="#">activity page</a>.
        </p>
      </div>
    </div>
  </li>
</ul>
```
