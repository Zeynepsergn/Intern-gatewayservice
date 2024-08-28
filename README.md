# Gateway Service
---------------------

Gateway sayesinde tüm istekler tek bir adresten geçerek eureka üzerindeki 
adlandırmalarına göre yönlendirmeler yapılır. Gateway den geçecek olan servisler 
config-server da config/gateway-service.yml altına tanımlanır. Tüm servislere ait 
swagger dokümantasyonları tek bir yerden yönetilir. Tüm servislerin id, servis-path 
tanımları burada yapılır.