# C# Development
## Operations System (enacpsulamiento e.g) 

``

using System;
using System.Threading;


namespace Expendedora1
{
    public abstract class Expendedora
    {
        #region Atributos
        private string _marca;
        private sbyte _temperatura;
        private ushort _cantProductos;
        private float _precio;
        #endregion

        #region Propiedades o encampsulado
        public sbyte Temperatura { 
            get => _temperatura; 
            set {
                if (value >= 10 && value < 21)
                {
                    _temperatura = value;
                }
                else 
                {
                    _temperatura = 18;
                
                
                }
             }
            }
``
### Development software bank system  in C#
- by Yael Valencia


