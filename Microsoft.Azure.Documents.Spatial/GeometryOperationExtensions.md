<Type Name="GeometryOperationExtensions" FullName="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions">
  <TypeSignature Language="C#" Value="public static class GeometryOperationExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GeometryOperationExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GeometryOperationExtensions" />
  <TypeSignature Language="F#" Value="type GeometryOperationExtensions = class" />
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
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="14d97-101">Auf unterstützten Vorgänge <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> Typ im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="14d97-101">Operations supported on <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> type in the Azure Cosmos DB service.</span></span> <span data-ttu-id="14d97-102">Diese Vorgänge in LINQ-Ausdrücke nur verwendet werden sollen, und es werden auf Server ausgewertet werden.</span><span class="sxs-lookup"><span data-stu-id="14d97-102">These operations are to be used in LINQ expressions only and will be evaluated on server.</span></span> <span data-ttu-id="14d97-103">Es ist keine Implementierung, die in der Clientbibliothek bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="14d97-103">There's no implementation provided in the client library.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Distance">
      <MemberSignature Language="C#" Value="public static double Distance (this Microsoft.Azure.Documents.Spatial.Geometry from, Microsoft.Azure.Documents.Spatial.Geometry to);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig float64 Distance(class Microsoft.Azure.Documents.Spatial.Geometry from, class Microsoft.Azure.Documents.Spatial.Geometry to) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Distance(Microsoft.Azure.Documents.Spatial.Geometry,Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Distance (from As Geometry, to As Geometry) As Double" />
      <MemberSignature Language="F#" Value="static member Distance : Microsoft.Azure.Documents.Spatial.Geometry * Microsoft.Azure.Documents.Spatial.Geometry -&gt; double" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Distance (from, to)" />
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
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
        <Parameter Name="to" Type="Microsoft.Azure.Documents.Spatial.Geometry" />
      </Parameters>
      <Docs>
        <param name="from"><span data-ttu-id="14d97-104">Erste <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-104">First <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <param name="to"><span data-ttu-id="14d97-105">Zweite <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-105">Second <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <summary>
            <span data-ttu-id="14d97-106">Der Abstand in Metern zwischen zwei Geometrien im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="14d97-106">Distance in meters between two geometries in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="14d97-107">Gibt eine Entfernung zwischen zwei Geometrien in Metern.</span><span class="sxs-lookup"><span data-stu-id="14d97-107">Returns distance in meters between two geometries.</span></span></returns>
        <remarks>
            <span data-ttu-id="14d97-108">Heute unterstützen diese Funktion nur Geometrien des <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> Typ.</span><span class="sxs-lookup"><span data-stu-id="14d97-108">Today this function support only geometries of <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> type.</span></span>
            </remarks>
        <example>
          <code><![CDATA[
            var distanceQuery = documents.Where(document => document.Location.Distance(new Point(20.1, 20)) < 20000);
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="Intersects">
      <MemberSignature Language="C#" Value="public static bool Intersects (this Microsoft.Azure.Documents.Spatial.Geometry geometry1, Microsoft.Azure.Documents.Spatial.Geometry geometry2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Intersects(class Microsoft.Azure.Documents.Spatial.Geometry geometry1, class Microsoft.Azure.Documents.Spatial.Geometry geometry2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Intersects(Microsoft.Azure.Documents.Spatial.Geometry,Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Intersects (geometry1 As Geometry, geometry2 As Geometry) As Boolean" />
      <MemberSignature Language="F#" Value="static member Intersects : Microsoft.Azure.Documents.Spatial.Geometry * Microsoft.Azure.Documents.Spatial.Geometry -&gt; bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Intersects (geometry1, geometry2)" />
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
        <Parameter Name="geometry1" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
        <Parameter Name="geometry2" Type="Microsoft.Azure.Documents.Spatial.Geometry" />
      </Parameters>
      <Docs>
        <param name="geometry1"><span data-ttu-id="14d97-109">Erste <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-109">First <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <param name="geometry2"><span data-ttu-id="14d97-110">Zweite <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-110">Second <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <summary>
            <span data-ttu-id="14d97-111">Überprüft, ob geometry1 geometry2 überschneidet.</span><span class="sxs-lookup"><span data-stu-id="14d97-111">Checks if geometry1 intersects with geometry2.</span></span>
            </summary>
        <returns><span data-ttu-id="14d97-112">Gibt "true" Wenn geometry1 geometry2, überschneidet, andernfalls "false" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="14d97-112">Returns true if geometry1 intersects with geometry2, otherwise returns false.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
          <code><![CDATA[
            var distanceQuery = documents.Where(document => document.Location.Intersects(new Point(20.1, 20)));
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsValid">
      <MemberSignature Language="C#" Value="public static bool IsValid (this Microsoft.Azure.Documents.Spatial.Geometry geometry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsValid(class Microsoft.Azure.Documents.Spatial.Geometry geometry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValid(Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="F#" Value="static member IsValid : Microsoft.Azure.Documents.Spatial.Geometry -&gt; bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValid geometry" />
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
        <Parameter Name="geometry" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
      </Parameters>
      <Docs>
        <param name="geometry"><span data-ttu-id="14d97-113">Die Geometrie auf Gültigkeit überprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="14d97-113">The geometry to check for validity.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="14d97-114">Bestimmt, ob die <paramref name="geometry" /> ist gültig und kann indizierte oder in nicht verwendete Abfragen von Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="14d97-114">Determines if the <paramref name="geometry" /> specified is valid and can be indexed or used in queries by Azure Cosmos DB service.</span></span>
            </para>
          <para>
            <span data-ttu-id="14d97-115">Wenn Sie eine Geometry-Instanz nicht gültig ist, wird es nicht indiziert werden.</span><span class="sxs-lookup"><span data-stu-id="14d97-115">If a geometry is not valid, it will not be indexed.</span></span> <span data-ttu-id="14d97-116">Auch während der Abfragezeit ungültige Geometrien entsprechen <c>undefined</c>.</span><span class="sxs-lookup"><span data-stu-id="14d97-116">Also during query time invalid geometries are equivalent to <c>undefined</c>.</span></span>
            </para>
        </summary>
        <returns>
          <span data-ttu-id="14d97-117"><c>"true"</c> Wenn Geometrie gültig ist.</span><span class="sxs-lookup"><span data-stu-id="14d97-117"><c>true</c> if geometry is valid.</span></span> <span data-ttu-id="14d97-118"><c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="14d97-118"><c>false</c> otherwise.</span></span></returns>
        <remarks>
            <span data-ttu-id="14d97-119">Diese Funktion unterstützt derzeit <paramref name="geometry" /> des Typs <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> und <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-119">Currently this function supports <paramref name="geometry" /> of type <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> and <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.</span></span>
            </remarks>
        <example>
          <para>
            <span data-ttu-id="14d97-120">In diesem Beispiel wählen Sie alle Dokumente auf die ungültige Geometrien enthalten, die nicht indiziert wurden.</span><span class="sxs-lookup"><span data-stu-id="14d97-120">This example select all the documents which contain invalid geometries which were not indexed.</span></span>
            </para>
          <code><![CDATA[
            var invalidDocuments = documents.Where(document => !document.Location.IsValid());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsValidDetailed">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.GeometryValidationResult IsValidDetailed (this Microsoft.Azure.Documents.Spatial.Geometry geometry);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.GeometryValidationResult IsValidDetailed(class Microsoft.Azure.Documents.Spatial.Geometry geometry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed(Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="F#" Value="static member IsValidDetailed : Microsoft.Azure.Documents.Spatial.Geometry -&gt; Microsoft.Azure.Documents.Spatial.GeometryValidationResult" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.IsValidDetailed geometry" />
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.GeometryValidationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="geometry" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
      </Parameters>
      <Docs>
        <param name="geometry"><span data-ttu-id="14d97-121">Die Geometrie auf Gültigkeit überprüft werden soll.</span><span class="sxs-lookup"><span data-stu-id="14d97-121">The geometry to check for validity.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="14d97-122">Bestimmt, ob die <paramref name="geometry" /> ist gültig und kann indizierte oder in nicht verwendete Abfragen von Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="14d97-122">Determines if the <paramref name="geometry" /> specified is valid and can be indexed or used in queries by Azure Cosmos DB service.</span></span>
            </para>
          <para>
            <span data-ttu-id="14d97-123">Wenn Sie eine Geometry-Instanz nicht gültig ist, wird es nicht indiziert werden.</span><span class="sxs-lookup"><span data-stu-id="14d97-123">If a geometry is not valid, it will not be indexed.</span></span> <span data-ttu-id="14d97-124">Auch während der Abfragezeit ungültige Geometrien entsprechen <c>undefined</c>.</span><span class="sxs-lookup"><span data-stu-id="14d97-124">Also during query time invalid geometries are equivalent to <c>undefined</c>.</span></span>
            </para>
        </summary>
        <returns><span data-ttu-id="14d97-125">Instanz des <see cref="T:Microsoft.Azure.Documents.Spatial.GeometryValidationResult" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-125">Instance of <see cref="T:Microsoft.Azure.Documents.Spatial.GeometryValidationResult" />.</span></span></returns>
        <remarks>
            <span data-ttu-id="14d97-126">Diese Funktion unterstützt derzeit <paramref name="geometry" /> des Typs <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> und <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-126">Currently this function supports <paramref name="geometry" /> of type <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> and <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.</span></span>
            </remarks>
        <example>
          <para>
            <span data-ttu-id="14d97-127">In diesem Beispiel wählen Sie alle Dokumente auf die ungültige Geometrien enthalten, die nicht indiziert wurden.</span><span class="sxs-lookup"><span data-stu-id="14d97-127">This example select all the documents which contain invalid geometries which were not indexed.</span></span>
            </para>
          <code><![CDATA[
            var invalidReason = documents.Where(document => !document.Location.IsValid()).Select(document => document.Location.IsValidDetailed());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="Within">
      <MemberSignature Language="C#" Value="public static bool Within (this Microsoft.Azure.Documents.Spatial.Geometry inner, Microsoft.Azure.Documents.Spatial.Geometry outer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Within(class Microsoft.Azure.Documents.Spatial.Geometry inner, class Microsoft.Azure.Documents.Spatial.Geometry outer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Within(Microsoft.Azure.Documents.Spatial.Geometry,Microsoft.Azure.Documents.Spatial.Geometry)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Within (inner As Geometry, outer As Geometry) As Boolean" />
      <MemberSignature Language="F#" Value="static member Within : Microsoft.Azure.Documents.Spatial.Geometry * Microsoft.Azure.Documents.Spatial.Geometry -&gt; bool" Usage="Microsoft.Azure.Documents.Spatial.GeometryOperationExtensions.Within (inner, outer)" />
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
        <Parameter Name="inner" Type="Microsoft.Azure.Documents.Spatial.Geometry" RefType="this" />
        <Parameter Name="outer" Type="Microsoft.Azure.Documents.Spatial.Geometry" />
      </Parameters>
      <Docs>
        <param name="inner"><span data-ttu-id="14d97-128">Innere <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-128">Inner <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <param name="outer"><span data-ttu-id="14d97-129">Äußere <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-129">Outer <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span></param>
        <summary>
            <span data-ttu-id="14d97-130">Bestimmt, ob <paramref name="inner" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> befindet sich vollständig innerhalb <paramref name="outer" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="14d97-130">Determines if <paramref name="inner" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> is fully contained inside <paramref name="outer" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="14d97-131"><c>"true"</c> Wenn <paramref name="inner" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> befindet sich vollständig innerhalb <paramref name="outer" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-131"><c>true</c> if <paramref name="inner" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> is fully contained inside <paramref name="outer" /><see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</span></span>
            <span data-ttu-id="14d97-132"><c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="14d97-132"><c>false</c> otherwise.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="14d97-133">Diese Funktion unterstützt derzeit <paramref name="inner" /> Geometrie des Typs <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> und äußere Geometrie des Typs <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.</span><span class="sxs-lookup"><span data-stu-id="14d97-133">Currently this function supports <paramref name="inner" /> geometry of type <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> and outer geometry of type <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.</span></span>
            </remarks>
        <example>
          <code><![CDATA[
            Polygon polygon = new Polygon(
                   new[]
                   {
                        new Position(10, 10),
                        new Position(30, 10),
                        new Position(30, 30),
                        new Position(10, 30),
                        new Position(10, 10)
                   });
            var withinQuery = documents.Where(document => document.Location.Within(polygon));
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>