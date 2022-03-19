
https://keras.io/guides/transfer_learning/   
### Transfer Learning
학습 데이터가 너무 적을 경우에 기존 대용량 학습 파라미터를 재이용.

* Layers & models 은 3개의 weight attributes를 가지고 있음.    
<pre>
layer = keras.layers.Dense(3)
layer.build((None, 4))  # Create the weights

print("weights:", len(layer.weights))
print("trainable_weights:", len(layer.trainable_weights))
print("non_trainable_weights:", len(layer.non_trainable_weights))
</pre>
<pre>
weights: 2
trainable_weights: 2
non_trainable_weights: 0
</pre>

https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html
