# Sistema-de-Avalia-o-Simples-v1
Sistema baseado em arrays e funções para avaliar dados através de média e regras condicionais.
função avaliarEnergias(energias)
    media = calcularMedia(energias)

    se media >= 8
        retornar "alta"
    senão se media >= 6
        retornar "media"
    senão
        retornar "baixa"
