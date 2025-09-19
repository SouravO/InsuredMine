Tab Count Badges
------------------
Each main content tab now supports an inline numeric count badge.

Markup Pattern (in `index.html`):
<a class="nav-link" ...>Label <span class="tab-count">N</span></a>

SCSS (`styles.scss`):
.nav-tabs .nav-link .tab-count {
  display: inline-block;
  min-width: 18px;
  padding: 2px 6px;
  margin-left: 6px;
  font-size: 10px;
  line-height: 1;
  border-radius: 12px;
  background: #F0F2F4;
  color: #697173;
  font-weight: 600;
  text-align: center;
}
.nav-tabs .nav-link.active .tab-count { background: $primary-color; color: #fff; }

Update Counts:
Change the inner text of <span class="tab-count"> for each tab as needed.
