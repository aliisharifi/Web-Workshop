<div dir="rtl">
<h1>
چرخه زندگی یک کامپوننت
</h1>

هر کامپوننت در ویو برای ساخته شدن و رندر شدن در صفحه از مراحلی عبور می‌کند.
در خود کامپوننت‌ها می‌توان به این مراحل دسترسی داشت و کد‌های لازم خود را برای هر قسمت را در آن‌ها اجرا کرد.
<br>
چرخه عمر کامل یک کامپوننت در تصویر زیر نمایان است:



![alt text](images/lifecycle.png)

در تصویر بالا مستطیل‌هایی مشاهده می‌کنید که توخالی هستند.
به ازای هر کدام از این‌ها در کامپوننت می‌توان از تابع آن‌ها استفاده کرد.
به طور مثال:

<div dir="ltr">

```vue
<script>
export default {
  created() {
    console.log('the component is now created')
  },
  mounted() {
    console.log('the component is now mounted')
  },
}
</script>
```

</div>

</div>
