qarma64: QARMA64.c
	sed -i 's/test_main_function/main/g' QARMA64.c
	@gcc -o $@ $^
	sed -i 's/main/test_main_function/g' QARMA64.c
	./qarma64
	rm qarma64

clean:
	@rm -f ./qarma64
