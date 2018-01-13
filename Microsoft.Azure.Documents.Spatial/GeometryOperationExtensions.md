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
            Auf unterstützten Vorgänge <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> Typ im Azure-Cosmos-DB-Dienst. Diese Vorgänge in LINQ-Ausdrücke nur verwendet werden sollen, und es werden auf Server ausgewertet werden. Es ist keine Implementierung, die in der Clientbibliothek bereitgestellt.
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
        <param name="from">Erste <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</param>
        <param name="to">Zweite <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</param>
        <summary>
            Der Abstand in Metern zwischen zwei Geometrien im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Gibt eine Entfernung zwischen zwei Geometrien in Metern.</returns>
        <remarks>
            Heute unterstützen diese Funktion nur Geometrien des <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> Typ.
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
        <param name="geometry1">Erste <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</param>
        <param name="geometry2">Zweite <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</param>
        <summary>
            Überprüft, ob geometry1 geometry2 überschneidet.
            </summary>
        <returns>Gibt "true" Wenn geometry1 geometry2, überschneidet, andernfalls "false" zurückgegeben.</returns>
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
        <param name="geometry">Die Geometrie auf Gültigkeit überprüft werden soll.</param>
        <summary>
          <para>
            Bestimmt, ob die <paramref name="geometry" /> ist gültig und kann indizierte oder in nicht verwendete Abfragen von Azure-Cosmos-DB-Dienst.
            </para>
          <para>
            Wenn Sie eine Geometry-Instanz nicht gültig ist, wird es nicht indiziert werden. Auch während der Abfragezeit ungültige Geometrien entsprechen <c>undefined</c>.
            </para>
        </summary>
        <returns>
          <c>"true"</c> Wenn Geometrie gültig ist. <c>"false"</c> andernfalls.</returns>
        <remarks>
            Diese Funktion unterstützt derzeit <paramref name="geometry" /> des Typs <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> und <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.
            </remarks>
        <example>
          <para>
            In diesem Beispiel wählen Sie alle Dokumente auf die ungültige Geometrien enthalten, die nicht indiziert wurden.
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
        <param name="geometry">Die Geometrie auf Gültigkeit überprüft werden soll.</param>
        <summary>
          <para>
            Bestimmt, ob die <paramref name="geometry" /> ist gültig und kann indizierte oder in nicht verwendete Abfragen von Azure-Cosmos-DB-Dienst.
            </para>
          <para>
            Wenn Sie eine Geometry-Instanz nicht gültig ist, wird es nicht indiziert werden. Auch während der Abfragezeit ungültige Geometrien entsprechen <c>undefined</c>.
            </para>
        </summary>
        <returns>Instanz des <see cref="T:Microsoft.Azure.Documents.Spatial.GeometryValidationResult" />.</returns>
        <remarks>
            Diese Funktion unterstützt derzeit <paramref name="geometry" /> des Typs <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> und <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.
            </remarks>
        <example>
          <para>
            In diesem Beispiel wählen Sie alle Dokumente auf die ungültige Geometrien enthalten, die nicht indiziert wurden.
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
        <param name="inner">Innere <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</param>
        <param name="outer">Äußere <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.</param>
        <summary>
            Bestimmt, ob <paramref name="inner" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> befindet sich vollständig innerhalb <paramref name="outer" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
          <c>"true"</c> Wenn <paramref name="inner" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> befindet sich vollständig innerhalb <paramref name="outer" /> <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" />.
            <c>"false"</c> andernfalls.
            </returns>
        <remarks>
            Diese Funktion unterstützt derzeit <paramref name="inner" /> Geometrie des Typs <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Point" /> und äußere Geometrie des Typs <see cref="F:Microsoft.Azure.Documents.Spatial.GeometryType.Polygon" />.
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