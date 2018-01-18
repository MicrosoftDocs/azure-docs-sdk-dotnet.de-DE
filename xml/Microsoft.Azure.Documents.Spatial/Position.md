<Type Name="Position" FullName="Microsoft.Azure.Documents.Spatial.Position">
  <TypeSignature Language="C#" Value="public sealed class Position : IEquatable&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Position extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Position" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Position&#xA;Implements IEquatable(Of Position)" />
  <TypeSignature Language="F#" Value="type Position = class&#xA;    interface IEquatable&lt;Position&gt;" />
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
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.Position&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.PositionJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="c939e-101">Eine Position, die durch ein Array der Zahlen in der Azure-Cosmos-DB-Dienst dargestellt wird.</span><span class="sxs-lookup"><span data-stu-id="c939e-101">A position is represented by an array of numbers in the Azure Cosmos DB service.</span></span> <span data-ttu-id="c939e-102">Es muss mindestens zwei Elemente, und möglicherweise weitere.</span><span class="sxs-lookup"><span data-stu-id="c939e-102">There must be at least two elements, and may be more.</span></span>
            </para>
      <para>
            <span data-ttu-id="c939e-103">Längengrad, Breitengrad, einsatzhöhe, muss die Reihenfolge der Elemente folgen.</span><span class="sxs-lookup"><span data-stu-id="c939e-103">The order of elements must follow longitude, latitude, altitude.</span></span>
            <span data-ttu-id="c939e-104">Eine beliebige Anzahl von zusätzlichen Elemente dürfen - Interpretation und die Bedeutung von zusätzlichen Elementen hängt von der Anwendung ist.</span><span class="sxs-lookup"><span data-stu-id="c939e-104">Any number of additional elements are allowed - interpretation and meaning of additional elements is up to the application.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Position (System.Collections.Generic.IList&lt;double&gt; coordinates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;float64&gt; coordinates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.#ctor(System.Collections.Generic.IList{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinates As IList(Of Double))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Position : System.Collections.Generic.IList&lt;double&gt; -&gt; Microsoft.Azure.Documents.Spatial.Position" Usage="new Microsoft.Azure.Documents.Spatial.Position coordinates" />
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
        <Parameter Name="coordinates" Type="System.Collections.Generic.IList&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinates">
            <span data-ttu-id="c939e-105">Positionswerte.</span><span class="sxs-lookup"><span data-stu-id="c939e-105">Position values.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c939e-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> Klasse im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="c939e-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Position (double longitude, double latitude);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(float64 longitude, float64 latitude) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.#ctor(System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (longitude As Double, latitude As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Position : double * double -&gt; Microsoft.Azure.Documents.Spatial.Position" Usage="new Microsoft.Azure.Documents.Spatial.Position (longitude, latitude)" />
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
        <Parameter Name="longitude" Type="System.Double" />
        <Parameter Name="latitude" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="longitude">
            <span data-ttu-id="c939e-107">Längenwert.</span><span class="sxs-lookup"><span data-stu-id="c939e-107">Longitude value.</span></span>
            </param>
        <param name="latitude">
            <span data-ttu-id="c939e-108">Breitenwert.</span><span class="sxs-lookup"><span data-stu-id="c939e-108">Latitude value.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c939e-109">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> Klasse im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="c939e-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Position (double longitude, double latitude, Nullable&lt;double&gt; altitude);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(float64 longitude, float64 latitude, valuetype System.Nullable`1&lt;float64&gt; altitude) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.#ctor(System.Double,System.Double,System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (longitude As Double, latitude As Double, altitude As Nullable(Of Double))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Position : double * double * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Documents.Spatial.Position" Usage="new Microsoft.Azure.Documents.Spatial.Position (longitude, latitude, altitude)" />
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
        <Parameter Name="longitude" Type="System.Double" />
        <Parameter Name="latitude" Type="System.Double" />
        <Parameter Name="altitude" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="longitude">
            <span data-ttu-id="c939e-110">Längenwert.</span><span class="sxs-lookup"><span data-stu-id="c939e-110">Longitude value.</span></span>
            </param>
        <param name="latitude">
            <span data-ttu-id="c939e-111">Breitenwert.</span><span class="sxs-lookup"><span data-stu-id="c939e-111">Latitude value.</span></span>
            </param>
        <param name="altitude">
            <span data-ttu-id="c939e-112">Optionale Höhe-Wert.</span><span class="sxs-lookup"><span data-stu-id="c939e-112">Optional altitude value.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c939e-113">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> Klasse im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="c939e-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> class in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Altitude">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Altitude { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Altitude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Position.Altitude" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Altitude As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Altitude : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Documents.Spatial.Position.Altitude" />
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
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c939e-114">Ruft die optionale Höhe im Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="c939e-114">Gets optional altitude in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c939e-115">Einsatzhöhe-Wert.</span><span class="sxs-lookup"><span data-stu-id="c939e-115">Altitude value.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Coordinates">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;double&gt; Coordinates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;float64&gt; Coordinates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Position.Coordinates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Coordinates As ReadOnlyCollection(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Coordinates : System.Collections.ObjectModel.ReadOnlyCollection&lt;double&gt;" Usage="Microsoft.Azure.Documents.Spatial.Position.Coordinates" />
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
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c939e-116">Ruft positionieren Koordinaten im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="c939e-116">Gets position coordinates in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c939e-117">Koordinatenwerte.</span><span class="sxs-lookup"><span data-stu-id="c939e-117">Coordinate values.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.Position other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.Position other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.Equals(Microsoft.Azure.Documents.Spatial.Position)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Position) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.Position -&gt; bool" Usage="position.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.Position" />
      </Parameters>
      <Docs>
        <param name="other">
          <span data-ttu-id="c939e-118"><see cref="T:Microsoft.Azure.Documents.Spatial.Position" />zu vergleichende <see cref="T:Microsoft.Azure.Documents.Spatial.Position" />.</span><span class="sxs-lookup"><span data-stu-id="c939e-118"><see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> to compare to this <see cref="T:Microsoft.Azure.Documents.Spatial.Position" />.</span></span></param>
        <summary>
            <span data-ttu-id="c939e-119">Bestimmt, ob diese <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> ist gleich der <paramref name="other" /> im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="c939e-119">Determines if this <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> is equal to the <paramref name="other" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="c939e-120"><c>"true"</c> Wenn die Objekte gleich sind.</span><span class="sxs-lookup"><span data-stu-id="c939e-120"><c>true</c> if objects are equal.</span></span> <span data-ttu-id="c939e-121"><c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="c939e-121"><c>false</c> otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="position.Equals obj" />
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
        <param name="obj"><span data-ttu-id="c939e-122">Die <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> , mit dem aktuellen Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c939e-122">The <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> to compare to the current object.</span></span> </param>
        <summary>
            <span data-ttu-id="c939e-123">Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> ist gleich dem aktuellen <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="c939e-123">Determines whether the specified <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> is equal to the current <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c939e-124">True, wenn das angegebene <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> ist mit dem aktuellen Objekt identisch ist, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c939e-124">true if the specified <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> is equal to the current object; otherwise, false.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Position.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="position.GetHashCode " />
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
            <span data-ttu-id="c939e-125">Dient als Hashfunktion für die <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> Typ im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="c939e-125">Serves as a hash function for the <see cref="T:Microsoft.Azure.Documents.Spatial.Position" /> type in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c939e-126">Ein Hashcode für die aktuelle <see cref="T:Microsoft.Azure.Documents.Spatial.Position" />.</span><span class="sxs-lookup"><span data-stu-id="c939e-126">A hash code for the current <see cref="T:Microsoft.Azure.Documents.Spatial.Position" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Latitude">
      <MemberSignature Language="C#" Value="public double Latitude { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Latitude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Position.Latitude" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Latitude As Double" />
      <MemberSignature Language="F#" Value="member this.Latitude : double" Usage="Microsoft.Azure.Documents.Spatial.Position.Latitude" />
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
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c939e-127">Ruft die Breite im Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="c939e-127">Gets latitude in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c939e-128">Breitenwert.</span><span class="sxs-lookup"><span data-stu-id="c939e-128">Latitude value.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Longitude">
      <MemberSignature Language="C#" Value="public double Longitude { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Longitude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Position.Longitude" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Longitude As Double" />
      <MemberSignature Language="F#" Value="member this.Longitude : double" Usage="Microsoft.Azure.Documents.Spatial.Position.Longitude" />
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
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c939e-129">Ruft den Längengrad im Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="c939e-129">Gets longitude in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c939e-130">Längenwert.</span><span class="sxs-lookup"><span data-stu-id="c939e-130">Longitude value.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>