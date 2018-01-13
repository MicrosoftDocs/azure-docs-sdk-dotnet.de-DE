<Type Name="Polygon" FullName="Microsoft.Azure.Documents.Spatial.Polygon">
  <TypeSignature Language="C#" Value="public sealed class Polygon : Microsoft.Azure.Documents.Spatial.Geometry, IEquatable&lt;Microsoft.Azure.Documents.Spatial.Polygon&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Polygon extends Microsoft.Azure.Documents.Spatial.Geometry implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.Polygon&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Polygon" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Polygon&#xA;Inherits Geometry&#xA;Implements IEquatable(Of Polygon)" />
  <TypeSignature Language="F#" Value="type Polygon = class&#xA;    inherit Geometry&#xA;    interface IEquatable&lt;Polygon&gt;" />
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
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.Polygon&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            Polygon-Geometry-Klasse in der Azure-Cosmos-DB-Dienst.
            </para>
      <para>
            Ein Polygon wird durch die Menge der "Polygon-Ringe" dargestellt. Jeder Ring wird geschlossen, Zeile Zeichenfolge.
            Erste Ring definiert externe Ring betrachtet. Alle nachfolgenden Ringe definieren "Löcher" in der externe Ring betrachtet.
            </para>
      <para>
            Ringe müssen angegeben werden, mit der linken Regel: Durchlaufen des Rings in der Reihenfolge seiner Punkte sollten dazu führen, interne Fläche des Polygons wird auf der linken Seite.
            </para>
    </summary>
    <remarks>To be added.</remarks>
    <example>
            In diesem Beispiel wird gezeigt, wie ein Polygon definieren, die kleine Teilmenge der Erde behandelt werden:
            <code language="c#"><![CDATA[
            var polygon = new Polygon(
                    new[]
                    {
                        new Position(20.0, 20.0),
                        new Position(30.0, 20.0),
                        new Position(30.0, 30.0),
                        new Position(20.0, 30.0)
                        new Position(20.0, 20.0)
                    });
            ]]></code></example>
    <example>
            In diesem Beispiel wird gezeigt, wie ein Polygon definieren, die Bereich umfasst mehr als eine Hemisphäre: (Beachten Sie, dass nur die Reihenfolge von Koordinaten umgekehrt wurde).
            <code language="c#"><![CDATA[
            var polygon = new Polygon(
            new[]
                    {
                    new Position(20.0, 20.0),
                        new Position(20.0, 30.0),
                        new Position(30.0, 30.0),
                        new Position(30.0, 20.0)
                        new Position(20.0, 20.0)
                        });
                    ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.LinearRing})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rings As IList(Of LinearRing))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon rings" />
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
        <Parameter Name="rings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
      </Parameters>
      <Docs>
        <param name="rings">
          <para>
            Polygon-Ringe.
            </para>
          <para>
            Erste Ring ist externe Ring betrachtet. Folgende Ringe definieren "Löcher" in den Polygon-.
            </para>
        </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; externalRingPositions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; externalRingPositions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.Position})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (externalRingPositions As IList(Of Position))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon externalRingPositions" />
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
        <Parameter Name="externalRingPositions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" />
      </Parameters>
      <Docs>
        <param name="externalRingPositions">
            Externe Ring polygonkoordinaten.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> -Klasse, aus der externe Ring betrachtet (Polygons enthält keine Lücken) im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Polygon (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings, Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; rings, class Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.LinearRing},Microsoft.Azure.Documents.Spatial.GeometryParams)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Polygon : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; * Microsoft.Azure.Documents.Spatial.GeometryParams -&gt; Microsoft.Azure.Documents.Spatial.Polygon" Usage="new Microsoft.Azure.Documents.Spatial.Polygon (rings, geometryParams)" />
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
        <Parameter Name="rings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
        <Parameter Name="geometryParams" Type="Microsoft.Azure.Documents.Spatial.GeometryParams" />
      </Parameters>
      <Docs>
        <param name="rings">
            Polygon-Ringe.
            </param>
        <param name="geometryParams">
            Zusätzliche Geometry-Parameter.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.Polygon other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.Polygon other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.Equals(Microsoft.Azure.Documents.Spatial.Polygon)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Polygon) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.Polygon -&gt; bool" Usage="polygon.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.Polygon" />
      </Parameters>
      <Docs>
        <param name="other">
          <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />zu vergleichende <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />.</param>
        <summary>
            Bestimmt, ob diese <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> ist gleich der <paramref name="other" /> im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
          <c>"true"</c> Wenn die Objekte gleich sind. <c>"false"</c> andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="polygon.Equals obj" />
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
        <param name="obj">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll. </param>
        <summary>
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> ist gleich dem aktuellen <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Polygon.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="polygon.GetHashCode " />
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
            Dient als Hashfunktion für die <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Typ im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein Hashcode für die aktuelle <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rings">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt; Rings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt; Rings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Polygon.Rings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Rings As ReadOnlyCollection(Of LinearRing)" />
      <MemberSignature Language="F#" Value="member this.Rings : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" Usage="Microsoft.Azure.Documents.Spatial.Polygon.Rings" />
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
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Polygon-Ringe in der Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Polygon-Ringe.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>