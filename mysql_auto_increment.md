# AUTO_INCREMENT


### AUTO_INCREMENTの確認
```
SELECT auto_increment FROM information_schema.tables WHERE table_name = '<table_name>';
```

### AUTO_INCREMENTの設定
```
ALTER TABLE <table_name> AUTO_INCREMENT= <Num>;
```
