```cpp
// 🎯 Perfil de Rodrigo Ramos 🚀
#include <iostream>
#include <vector>
#include <string>

class IngenieroSoftware {
public:
    std::string nombre = "Rodrigo Alejandro Ramos Lozano";
    std::string titulo = "🖥️ Ingeniero en Desarrollo de Software";
    std::string institucion = "🏫 CETI Colomos, Guadalajara, Jalisco, México";
    std::vector<std::string> habilidades = {
        "💻 Desarrollo web",
        "⚡ Programación en C++, PHP, JavaScript",
        "🗄️ Bases de datos MySQL",
        "🔧 Gestión de versiones con Git",
        "📊 Análisis y solución de problemas"
    };

    void presentacion() {
        std::cout << "👋 ¡Hola! Soy " << nombre << ", un " << titulo << " apasionado por el desarrollo de software."
                  << "\n🚀 Me especializo en crear soluciones eficientes y escalables."
                  << "\n🎯 Siempre en busca de aprender y mejorar mis habilidades técnicas."
                  << "\n\n📌 Mis habilidades clave incluyen:" << std::endl;
        for (const auto& skill : habilidades) {
            std::cout << "  🔹 " << skill << std::endl;
        }
        std::cout << "\n⚡ Siempre listo para enfrentar nuevos desafíos y seguir aprendiendo. 💡" << std::endl;
    }
};

int main() {
    IngenieroSoftware rodrigo;
    rodrigo.presentacion();
    return 0;
}
