<Type Name="LinearRing" FullName="Microsoft.Azure.Documents.Spatial.LinearRing">
  <TypeSignature Language="C#" Value="public sealed class LinearRing : IEquatable&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LinearRing extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.LinearRing&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.LinearRing" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LinearRing&#xA;Implements IEquatable(Of LinearRing)" />
  <TypeSignature Language="F#" Value="type LinearRing = class&#xA;    interface IEquatable&lt;LinearRing&gt;" />
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
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.LinearRing&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.LinearRingJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Ein <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> ist LineString mit 4 oder mehr Positionen geschlossen. Die ersten und letzten Positionen sind äquivalent (sie darstellen entsprechende Punkte).
            Obwohl eine <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> nicht explizit dargestellt als einen GeoJSON-Geometry-Datentyp wird bezeichnet, die in der <see cref="T:Microsoft.Azure.Documents.Spatial.Polygon" /> Geometry-Typdefinition in der Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinearRing (System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; coordinates);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; coordinates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinearRing.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Documents.Spatial.Position})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinates As IList(Of Position))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.LinearRing : System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.Spatial.Position&gt; -&gt; Microsoft.Azure.Documents.Spatial.LinearRing" Usage="new Microsoft.Azure.Documents.Spatial.LinearRing coordinates" />
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
            Die Koordinaten. 4 oder mehr Positionen. Die ersten und letzten Positionen sind äquivalent (sie darstellen entsprechende Punkte).
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.LinearRing other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.LinearRing other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinearRing.Equals(Microsoft.Azure.Documents.Spatial.LinearRing)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As LinearRing) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.LinearRing -&gt; bool" Usage="linearRing.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.LinearRing" />
      </Parameters>
      <Docs>
        <param name="other">
          <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />Dieses Objekt verglichen werden soll.</param>
        <summary>
            Bestimmt, ob diese <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> ist gleich der <paramref name="other" /> im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
          <c>"true"</c> Wenn lineare Rufzeichen gleich sind. <c>"false"</c> andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinearRing.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="linearRing.Equals obj" />
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
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> ist gleich dem aktuellen <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            "true", wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist; andernfalls "false".
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.LinearRing.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="linearRing.GetHashCode " />
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
            Dient als Hashfunktion für die <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> Positionen im Azure-Cosmos-DB-Dienst. 
            </summary>
        <returns>
            Ein Hashcode für die aktuelle <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Positions">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.Position&gt; Positions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.Azure.Documents.Spatial.Position&gt; Positions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.LinearRing.Positions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Positions As ReadOnlyCollection(Of Position)" />
      <MemberSignature Language="F#" Value="member this.Positions : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.Position&gt;" Usage="Microsoft.Azure.Documents.Spatial.LinearRing.Positions" />
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
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.Documents.Spatial.Position&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" /> Positionen im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Positionen von der <see cref="T:Microsoft.Azure.Documents.Spatial.LinearRing" />.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>