<Type Name="LineString" FullName="Microsoft.Azure.Documents.Spatial.LineString">
  <TypeSignature Language="C#" Value="public sealed class LineString : Microsoft.Azure.Documents.Spatial.Geometry, IEquatable&lt;Microsoft.Azure.Documents.Spatial.LineString&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LineString extends Microsoft.Azure.Documents.Spatial.Geometry implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.LineString&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.LineString" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LineString&#xA;Inherits Geometry&#xA;Implements IEquatable(Of LineString)" />
  <TypeSignature Language="F#" Value="type LineString = class&#xA;    inherit Geometry&#xA;    interface IEquatable&lt;LineString&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Spatial.Geometry</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.LineString&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="aa087-101">Stellt eine Geometry-Instanz verbundenen Liniensegmente besteht.</span><span class="sxs-lookup"><span data-stu-id="aa087-101">Represents a geometry consisting of connected line segments.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LineString (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; coordinates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; coordinates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LineString.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.Position})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinates As IList(Of Position))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.LineString : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; -&gt; Microsoft.Azure.Documents.Spatial.LineString" Usage="new Microsoft.Azure.Documents.Spatial.LineString coordinates" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinates">
            <span data-ttu-id="aa087-102">Liste der Positionen die Zeichenfolge durchläuft.</span><span class="sxs-lookup"><span data-stu-id="aa087-102">List of positions through which the line string goes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa087-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="aa087-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" /> class.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LineString (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; coordinates, Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; coordinates, class Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LineString.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.Position},Microsoft.Azure.Documents.Spatial.GeometryParams)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.LineString : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; * Microsoft.Azure.Documents.Spatial.GeometryParams -&gt; Microsoft.Azure.Documents.Spatial.LineString" Usage="new Microsoft.Azure.Documents.Spatial.LineString (coordinates, geometryParams)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" />
        <Parameter Name="geometryParams" Type="Microsoft.Azure.Documents.Spatial.GeometryParams" />
      </Parameters>
      <Docs>
        <param name="coordinates">
            <span data-ttu-id="aa087-104">Die Koordinaten.</span><span class="sxs-lookup"><span data-stu-id="aa087-104">The coordinates.</span></span>
            </param>
        <param name="geometryParams">
            <span data-ttu-id="aa087-105">Zusätzliche Geometry-Parameter.</span><span class="sxs-lookup"><span data-stu-id="aa087-105">Additional geometry parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="aa087-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="aa087-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.LineString other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.LineString other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LineString.Equals(Microsoft.Azure.Documents.Spatial.LineString)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As LineString) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.LineString -&gt; bool" Usage="lineString.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.LineString" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="aa087-107">LineString zu vergleichende <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" />.</span><span class="sxs-lookup"><span data-stu-id="aa087-107">LineString to compare to this <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" />.</span></span></param>
        <summary>
            <span data-ttu-id="aa087-108">Bestimmt, ob diese <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" /> ist gleich der <paramref name="other" />.</span><span class="sxs-lookup"><span data-stu-id="aa087-108">Determines if this <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" /> is equal to the <paramref name="other" />.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="aa087-109"><c>"true"</c> wenn Zeile Zeichenfolgen gleich sind.</span><span class="sxs-lookup"><span data-stu-id="aa087-109"><c>true</c> if line strings are equal.</span></span> <span data-ttu-id="aa087-110"><c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="aa087-110"><c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LineString.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="lineString.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="aa087-111">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="aa087-111">The object to compare with the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="aa087-112">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" /> und das aktuelle <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" /> gleich sind.</span><span class="sxs-lookup"><span data-stu-id="aa087-112">Determines whether the specified <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" /> is equal to the current <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa087-113">True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="aa087-113">true if the specified object is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LineString.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="lineString.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aa087-114">Dient als Hashfunktion für die <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" /> Typ.</span><span class="sxs-lookup"><span data-stu-id="aa087-114">Serves as a hash function for the <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" /> type.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="aa087-115">Ein Hashcode für die aktuelle <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" />.</span><span class="sxs-lookup"><span data-stu-id="aa087-115">A hash code for the current <see cref="T:Microsoft.Azure.Documents.Spatial.LineString" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Positions">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.Position&gt; Positions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; Positions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.LineString.Positions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Positions As ReadOnlyCollection(Of Position)" />
      <MemberSignature Language="F#" Value="member this.Positions : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" Usage="Microsoft.Azure.Documents.Spatial.LineString.Positions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("coordinates", Order=1, Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.Position&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa087-116">Ruft die Zeile Positionen in Zeichenfolgen ab.</span><span class="sxs-lookup"><span data-stu-id="aa087-116">Gets line string positions.</span></span>
            </summary>
        <value>
            <span data-ttu-id="aa087-117">Die Positionen der Zeile Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="aa087-117">Positions of the line string.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>