<Type Name="Point" FullName="Microsoft.Azure.Documents.Spatial.Point">
  <TypeSignature Language="C#" Value="public sealed class Point : Microsoft.Azure.Documents.Spatial.Geometry, IEquatable&lt;Microsoft.Azure.Documents.Spatial.Point&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Point extends Microsoft.Azure.Documents.Spatial.Geometry implements class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Spatial.Point&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Point" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Point&#xA;Inherits Geometry&#xA;Implements IEquatable(Of Point)" />
  <TypeSignature Language="F#" Value="type Point = class&#xA;    inherit Geometry&#xA;    interface IEquatable&lt;Point&gt;" />
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
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Spatial.Point&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Zeigen Sie im Azure-Cosmos-DB-Dienst Geometry-Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Point (Microsoft.Azure.Documents.Spatial.Position position);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Spatial.Position position) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.#ctor(Microsoft.Azure.Documents.Spatial.Position)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Point : Microsoft.Azure.Documents.Spatial.Position -&gt; Microsoft.Azure.Documents.Spatial.Point" Usage="new Microsoft.Azure.Documents.Spatial.Point position" />
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
        <Parameter Name="position" Type="Microsoft.Azure.Documents.Spatial.Position" />
      </Parameters>
      <Docs>
        <param name="position">
            Die Position des Punkts.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Point (Microsoft.Azure.Documents.Spatial.Position position, Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Documents.Spatial.Position position, class Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.#ctor(Microsoft.Azure.Documents.Spatial.Position,Microsoft.Azure.Documents.Spatial.GeometryParams)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Point : Microsoft.Azure.Documents.Spatial.Position * Microsoft.Azure.Documents.Spatial.GeometryParams -&gt; Microsoft.Azure.Documents.Spatial.Point" Usage="new Microsoft.Azure.Documents.Spatial.Point (position, geometryParams)" />
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
        <Parameter Name="position" Type="Microsoft.Azure.Documents.Spatial.Position" />
        <Parameter Name="geometryParams" Type="Microsoft.Azure.Documents.Spatial.GeometryParams" />
      </Parameters>
      <Docs>
        <param name="position">
            Zeigen Sie die Koordinaten.
            </param>
        <param name="geometryParams">
            Zusätzliche Geometry-Parameter.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Point (double longitude, double latitude);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(float64 longitude, float64 latitude) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.#ctor(System.Double,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (longitude As Double, latitude As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Point : double * double -&gt; Microsoft.Azure.Documents.Spatial.Point" Usage="new Microsoft.Azure.Documents.Spatial.Point (longitude, latitude)" />
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
            Der Längengrad des Punkts.
            </param>
        <param name="latitude">
            Der Breitengrad dieses Punkts.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Spatial.Point other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Spatial.Point other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.Equals(Microsoft.Azure.Documents.Spatial.Point)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Point) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Spatial.Point -&gt; bool" Usage="point.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Spatial.Point" />
      </Parameters>
      <Docs>
        <param name="other">
          <see cref="T:Microsoft.Azure.Documents.Spatial.Point" />zu vergleichende <see cref="T:Microsoft.Azure.Documents.Spatial.Point" />.</param>
        <summary>
            Bestimmt, ob diese <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> gleich <paramref name="other" /> im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
          <c>"true"</c> Wenn die Objekte gleich sind. <c>"false"</c> andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="point.Equals obj" />
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
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> ist gleich dem aktuellen <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> im Azure-Cosmos-DB-Dienst.
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Point.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="point.GetHashCode " />
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
            Dient als Hashfunktion für die <see cref="T:Microsoft.Azure.Documents.Spatial.Point" /> Typ im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein Hashcode für die aktuelle Geometrie.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Position">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.Position Position { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Spatial.Position Position" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Point.Position" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Position As Position" />
      <MemberSignature Language="F#" Value="member this.Position : Microsoft.Azure.Documents.Spatial.Position" Usage="Microsoft.Azure.Documents.Spatial.Point.Position" />
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.Position</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft zeigen Koordinaten im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Die Koordinaten des Punkts.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>