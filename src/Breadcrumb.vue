<template>

<section>
    <!--  With a tag -->
    <o-breadcrumb
        tag="div"
        variant="warning"
        separator="has-slash-separator"
        size="large"
        align="left">
        <o-breadcrumb-item tag="a" href="/">Home</o-breadcrumb-item>
        <o-breadcrumb-item tag="a" href="/" disabled="true">Docs</o-breadcrumb-item>
        <o-breadcrumb-item tag="a" href="/breadcrumb" active="true" active-variant="warning">Breadcrumb</o-breadcrumb-item>
    </o-breadcrumb>
    <!--  With router-link tag -->
    <o-breadcrumb
        tag="div"
        separator="has-chevron-separator"
        size="medium"
        align="left">
        <o-breadcrumb-item tag="router-link" to="/" active-variant="warning">Home</o-breadcrumb-item>
        <o-breadcrumb-item tag="router-link" to="/" active-variant="warning" disabled="true" >Docs</o-breadcrumb-item>
        <o-breadcrumb-item tag="router-link" to="/breadcrumb" active-variant="warning">Breadcrumb</o-breadcrumb-item>
    </o-breadcrumb>
   
    <o-breadcrumb
        tag="div"
        separator="has-chevron-separator"
        size="small"
        align="left">
        <o-breadcrumb-item tag="router-link" to="/" active-variant="warning">Home</o-breadcrumb-item>
        <o-breadcrumb-item tag="router-link" to="/" active-variant="warning"disabled="true">Docs</o-breadcrumb-item>
        <o-breadcrumb-item tag="router-link" to="/breadcrumb" active-variant="warning">Breadcrumb</o-breadcrumb-item>
    </o-breadcrumb>
   
    <o-breadcrumb
        tag="div"   
        separator="has-arrow-separator"
        size="medium"
        align="centered">
        <o-breadcrumb-item tag="a" href="/" icon-left="home">Home</o-breadcrumb-item>
        <o-breadcrumb-item tag="a" href="/" icon-left="plus" disabled="true">Docs</o-breadcrumb-item>
        <o-breadcrumb-item tag="a" href="/breadcrumb" icon-left="location" active-variant="warning" active="true">Breadcrumb</o-breadcrumb-item>
    </o-breadcrumb>
   
    <o-breadcrumb
        tag="div"
        separator="has-dot-separator"
        size="medium"
        align="right">
        <o-breadcrumb-item tag="a" href="/" icon-left="home">Home</o-breadcrumb-item>
        <o-breadcrumb-item tag="a" href="/" icon-left="plus" disabled="true">Docs</o-breadcrumb-item>
        <o-breadcrumb-item tag="a" href="/breadcrumb" icon-left="location" active-variant="warning" active="true">Breadcrumb</o-breadcrumb-item>
    </o-breadcrumb>
</section>
</template>
<script setup='true'></script>