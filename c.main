int main(){
    stdio_init_all();
    gpio_init(9);
    gpio_init(25);
    gpio_set_dir(9,false);
    gpio_set_dir(25,true);
    while(1){
        char val=gpio_get(9);
        char val1=gpio_get(25);
        if(val==1 && val1=0){
            gpio_put(25,true);
        }
        if(val==1 && val1==1){
            gpio_put(25,false);
        }
        sleep_ms(500);
    }
}
