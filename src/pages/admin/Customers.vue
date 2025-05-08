<template>
  <form data-v-12a5da11="" class="p-2 mb-2">
    <div data-v-de519510="" data-v-12a5da11="">
      <!---->
      <div data-v-de519510="" class="d-flex flex-wrap gap-3">
        <div data-v-de519510="" class="param-item">
          ``
          <label data-v-de519510="" class="d-block pb-1"
            ><div data-v-de519510="">
              <strong data-v-de519510="" class="text-muted"
                ><small data-v-de519510="">상품명</small
                ><small data-v-de519510="" class="ms-1" style="color: tomato; display: none">*</small></strong
              >
            </div></label
          >
          <div data-v-c6bc9a96="" data-v-de519510="" class="">
            <span data-v-c6bc9a96="" class=""><input data-v-c6bc9a96="" class="form-control" /><!----><!----></span
            ><!----><!----><!----><!----><!---->
          </div>
        </div>
        <div data-v-de519510="" class="param-item">
          <label data-v-de519510="" class="d-block pb-1"
            ><div data-v-de519510="">
              <strong data-v-de519510="" class="text-muted"
                ><small data-v-de519510="">조회 기간</small
                ><small data-v-de519510="" class="ms-1" style="color: tomato; display: none">*</small></strong
              >
            </div></label
          >
          <div data-v-c6bc9a96="" data-v-de519510="" class="">
            <div data-v-c6bc9a96="" class="d-flex">
              <div data-v-c6bc9a96="" class="w-100 xmx-datepicker xmx-datepicker-range">
                <div class="xmx-input-wrapper">
                  <input name="date" type="text" autocomplete="off" placeholder="" class="xmx-input" /><i
                    class="xmx-icon-calendar"
                    ><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1024 1024" width="1em" height="1em">
                      <path
                        d="M940.218182 107.054545h-209.454546V46.545455h-65.163636v60.50909H363.054545V46.545455H297.890909v60.50909H83.781818c-18.618182 0-32.581818 13.963636-32.581818 32.581819v805.236363c0 18.618182 13.963636 32.581818 32.581818 32.581818h861.090909c18.618182 0 32.581818-13.963636 32.581818-32.581818V139.636364c-4.654545-18.618182-18.618182-32.581818-37.236363-32.581819zM297.890909 172.218182V232.727273h65.163636V172.218182h307.2V232.727273h65.163637V172.218182h176.872727v204.8H116.363636V172.218182h181.527273zM116.363636 912.290909V442.181818h795.927273v470.109091H116.363636z"></path></svg
                  ></i>
                </div>
              </div>
              <div data-v-c6bc9a96="" class="btn-group ms-1 w-100">
                <button data-v-c6bc9a96="" type="button" class="btn btn-light border min-w-fit">지난주</button
                ><button data-v-c6bc9a96="" type="button" class="btn btn-light border min-w-fit">다음주</button
                ><button data-v-c6bc9a96="" type="button" class="btn btn-light border min-w-fit">초기화</button>
              </div>
            </div>
            <!----><!----><!----><!----><!---->
          </div>
        </div>
        <div data-v-de519510="" class="param-item">
          <label data-v-de519510="" class="d-block pb-1"
            ><div data-v-de519510="">
              <strong data-v-de519510="" class="text-muted"
                ><small data-v-de519510="">판매여부</small
                ><small data-v-de519510="" class="ms-1" style="color: tomato; display: none">*</small></strong
              >
            </div></label
          >
          <div data-v-c6bc9a96="" data-v-de519510="" class="">
            <div data-v-c6bc9a96="" class="btn-group">
              <label data-v-c6bc9a96="" class="btn btn-light text-primary undefined"
                ><input
                  data-v-c6bc9a96=""
                  tabindex="0"
                  type="radio"
                  name="sell_status_radio"
                  class="btn-check"
                  value="" />전체</label
              ><label data-v-c6bc9a96="" class="btn btn-light border undefined"
                ><input
                  data-v-c6bc9a96=""
                  tabindex="0"
                  type="radio"
                  name="sell_status_radio"
                  class="btn-check"
                  value="판매" />판매</label
              ><label data-v-c6bc9a96="" class="btn btn-light border undefined"
                ><input
                  data-v-c6bc9a96=""
                  tabindex="0"
                  type="radio"
                  name="sell_status_radio"
                  class="btn-check"
                  value="미판매" />미판매</label
              >
            </div>
            <!----><!----><!----><!----><!---->
          </div>
        </div>
        <div data-v-de519510="" class="param-item">
          <label data-v-de519510="" class="d-block pb-1"
            ><div data-v-de519510="">
              <strong data-v-de519510="" class="text-muted"
                ><small data-v-de519510="">진열여부</small
                ><small data-v-de519510="" class="ms-1" style="color: tomato; display: none">*</small></strong
              >
            </div></label
          >
          <div data-v-c6bc9a96="" data-v-de519510="" class="">
            <div data-v-c6bc9a96="" class="btn-group">
              <label data-v-c6bc9a96="" class="btn btn-light text-primary undefined"
                ><input
                  data-v-c6bc9a96=""
                  tabindex="0"
                  type="radio"
                  name="display_status_radio"
                  class="btn-check"
                  value="" />전체</label
              ><label data-v-c6bc9a96="" class="btn btn-light border undefined"
                ><input
                  data-v-c6bc9a96=""
                  tabindex="0"
                  type="radio"
                  name="display_status_radio"
                  class="btn-check"
                  value="진열" />진열</label
              ><label data-v-c6bc9a96="" class="btn btn-light border undefined"
                ><input
                  data-v-c6bc9a96=""
                  tabindex="0"
                  type="radio"
                  name="display_status_radio"
                  class="btn-check"
                  value="미진열" />미진열</label
              >
            </div>
            <!----><!----><!----><!----><!---->
          </div>
        </div>
        <div data-v-de519510="" class="param-item">
          <label data-v-de519510="" class="d-block pb-1"
            ><div data-v-de519510="">
              <strong data-v-de519510="" class="text-muted"
                ><small data-v-de519510="">할인여부</small
                ><small data-v-de519510="" class="ms-1" style="color: tomato; display: none">*</small></strong
              >
            </div></label
          >
          <div data-v-c6bc9a96="" data-v-de519510="" class="">
            <div data-v-c6bc9a96="" class="btn-group">
              <label data-v-c6bc9a96="" class="btn btn-light text-primary undefined"
                ><input
                  data-v-c6bc9a96=""
                  tabindex="0"
                  type="radio"
                  name="discount_status_radio"
                  class="btn-check"
                  value="" />전체</label
              ><label data-v-c6bc9a96="" class="btn btn-light border undefined"
                ><input
                  data-v-c6bc9a96=""
                  tabindex="0"
                  type="radio"
                  name="discount_status_radio"
                  class="btn-check"
                  value="할인" />할인</label
              ><label data-v-c6bc9a96="" class="btn btn-light border undefined"
                ><input
                  data-v-c6bc9a96=""
                  tabindex="0"
                  type="radio"
                  name="discount_status_radio"
                  class="btn-check"
                  value="미할인" />미할인</label
              >
            </div>
            <!----><!----><!----><!----><!---->
          </div>
        </div>
        <!----><!----><!----><!----><!---->
      </div>
      <div data-v-de519510="" class="pt-2"></div>
      <div data-v-de519510="">
        <span data-v-12a5da11="" data-v-de519510=""
          ><button
            data-v-12a5da11=""
            data-v-de519510=""
            type="submit"
            class="disabled:opacity-50 disabled:cursor-default no-underline cursor-pointer rounded bg-blue-600 px-2.5 py-1.5 text-[13px] font-semibold text-white shadow-sm enabled:hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-600 undefined">
            <div data-v-12a5da11="" class="flex items-center gap-1" data-v-de519510=""><!----><!---->검색<!----></div>
          </button></span
        >
        <div data-v-12a5da11="" data-v-de519510="" class="ps-1 d-inline-block">
          <button data-v-12a5da11="" data-v-de519510="" type="reset" class="btn btn-light border undefined">
            <div data-v-12a5da11="" class="flex items-center gap-1" data-v-de519510=""><!----><!---->초기화<!----></div>
          </button>
        </div>
      </div>
    </div>
  </form>
</template>
