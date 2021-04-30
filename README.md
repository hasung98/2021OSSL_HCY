# 2021OSSL_HCY

This is an H!
-------------

# one
## two
### three
#### four
##### five
###### six

> first block
>   > second block
>   >   > third block

> block
> + list
>   + list2

* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑

* 1단계
  - 2단계
    + 3단계
      + 4단계

writing

    with 'tab' and 'enter' in between

end of writing

<pre><code>{void uploadProductData(Product *p/*, int index*/){
	FILE *fp;
	fp = fopen("productData.txt", "wt");
	for(int i = 0; i < index; i++){
		fprintf(fp, "%.2f %d %.2f %d %s\n", p->weight, p->price, p->rate, p->numRate, p->name);
	}

	fclose(fp);
	printf("==> 제품  저장됨!\n");
}}</code></pre>