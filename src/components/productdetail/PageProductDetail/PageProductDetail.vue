<i18n src="./PageProductDetail.txt"></i18n>
<script src="./PageProductDetail.js"></script>

<template>
  <!-- <div>
    <div id="pdp-page">
      <div class="container">
        <div class="row">
          <div class="col-xs-12 breadcrumb-col">
          <Breadcrumb />
          </div>
        </div>
        <div class="row product-info-row-pdp">
          <!-- {{> catalog/pdp/product-info product=content.product deliveryRates=content.deliveryRates}}
        <ProductInfo :sku="sku" />
        </div>
      </div>
    </div>
    <!--<div class="pdp-page-review">
      <!--<div class="container">
        <!--<div class="row">
          <!--<div class="col-sm-12">
            <!--<p class="text-center text-uppercase may-like">
              <!--{{ $t('suggestions.title') }}
            <!--</p>
          <!--</div>
        <!--</div>
        <!-- <div class="row">
          {{#each content.suggestions.list}}
          <div class="col-xs-12 col-sm-6 col-md-3">
            {{> catalog/product-thumbnail thumbnail=this index=@index}}
          </div>
          {{/each}}
      </div>
        <!--<hr class="hr">
        <!-- {{> catalog/pdp/reviews}}
      <!--</div>
    <!--</div>
  </div> -->
  <!-- <div v-if="product">
    <div data-test="product-gallery"
         class="col-md-4 col-md-offset-1 col-sm-6 product-gallery">
      <ProductGallery :sku="sku" />
    </div>
    <div data-test="product-data"
         class="col-sm-6 product-description">
      <div class="row">
        <div class="col-sm-12">
          <h1 data-test="product-name"
              class="text-uppercase pdp-product-title">
            {{ currentProduct.name }}
          </h1>
          <span data-test="product-sku"
                class="grey-p quickview-sku">
              {{ sku }}
            </span>
        </div>
      </div>
      <div class="row">
        <div class="col-sm-12">
          <!-- {{> catalog/product-rating }}
</div>
</div>
<div class="row">
  <div class="col-sm-12">
    <p class="pdp-product-description view-details more" data-text-show="$t('showMore')"
      data-text-hide="$t('showLess')">
    </p>
  </div>
</div>
<div class="row">
  <div v-if="hasPrice" class="col-sm-12">
    <p class="product-price">
      <BasePrice :price="matchingVariant.price" />
    </p>
  </div>
</div>
<VariantSelector :sku="sku" />
<AddToCartForm :sku="sku" />
<!-- {{> catalog/add-to-wishlist-btn}}
      {{> catalog/reserve-in-store-btn}}
<div class="row">
  <div class="col-sm-12">
    <!-- {{> catalog/product-availability availability=product.availability}}
  </div>
</div>
<DetailsSection :sku="sku" />
<SocialMediaLinks />
</div>
</div> -->
  <div class="product-details-area pt-50 pb-50">
    <div class="custom-container">
      <ProductInfo :sku="sku" />
    </div>
  </div>
</template>
