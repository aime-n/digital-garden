Possui 2 componentes:
1. Componente aleatório: variável resposta $Y$
	- Segue alguma distribuição da [[Exponential Family]]
	- $Y|X \sim \mathcal{N} (\mu(X), \sigma^2)$ onde $\mu = \mu(X) = \mathbb{E}(Y|X)$  
	



2. Link function $g$
	- Link entre a variável aleatória e as covariáveis
	- $X = (X^{(1)}, X^{(2)},..., X^{(p)})^\mathsf{T}: \mu(X) = X^\mathsf{T} \beta$             
	
	- $g(\mu(X)) = X^\mathsf{T}\beta$  onde $\mu(X) = X^\mathsf{T} \beta$  
	