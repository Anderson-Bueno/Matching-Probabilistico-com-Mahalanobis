# Falta de confiança nas segmentações comportamentais em ambientes com dados imperfeitos

Organizações enfrentavam dificuldades para:

Tomar decisões estratégicas (como campanhas, preços ou suporte) com base em perfis comportamentais mal definidos;

Confiar nas segmentações existentes, que eram estáticas, frágeis e vulneráveis a ruído, outliers ou amostragens enviesadas;

Manter consistência entre dados brutos e decisões analíticas, por não haver uma camada estatística robusta entre ambos.

Antes do modelo:

Segmentações baseadas em regras manuais ou heurísticas simples;

Distâncias Euclidianas frágeis usadas para medir similaridade entre perfis, altamente sensíveis a escala, colinearidade e outliers;

Campanhas inconsistentes e classificações erradas de clientes por ruído nos dados.

O modelo resolve ao:

Aplicar distância de Mahalanobis com robustez estatística (via MinCovDet) para identificar o perfil mais provável de um cliente, mesmo em dados com baixa qualidade estatística;

Transformar distâncias em probabilidades via Softmax, criando uma camada probabilística interpretável e auditável;

Proteger contra falhas numéricas, com fallback automático para distância Euclidiana;

Modularizar e escalar a solução com Spark no Databricks, viabilizando aplicação em larga escala.

Esse modelo atua como ponte crítica entre dados brutos e decisões analíticas confiáveis, entregando não só robustez estatística, mas também valor organizacional direto.
