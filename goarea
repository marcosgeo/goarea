package goarea

import "math"

// Pi é uma proporção numerica definida pela relação entre
// o perimetro de uma circunferencia e o seu diametro
const Pi = 3.14159216

// Circ é responsável por calcular a área da circunferencia
func Circ(raio float64) float64 {
	return math.Pow(raio, 2) * Pi
}

// Rect é responsavel por calcular a área de um retangulo
func Rect(base, altura float64) float64 {
	return base * altura
}

// Função privada, não é visivel fora do pacote
func _TrianguloEq(base, altura float64) float64 {
	return (base * altura) / 2.0
}
