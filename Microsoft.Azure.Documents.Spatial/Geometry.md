<Type Name="Geometry" FullName="Microsoft.Azure.Documents.Spatial.Geometry">
  <TypeSignature Language="C#" Value="public abstract class Geometry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Geometry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Geometry" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Geometry" />
  <TypeSignature Language="F#" Value="type Geometry = class" />
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
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.GeometryJsonConverter))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject(Newtonsoft.Json.MemberSerialization.OptIn)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Basisklasse für räumliche Geometry-Objekten in der Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Geometry (Microsoft.Azure.Documents.Spatial.GeometryType type, Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Documents.Spatial.GeometryType type, class Microsoft.Azure.Documents.Spatial.GeometryParams geometryParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Geometry.#ctor(Microsoft.Azure.Documents.Spatial.GeometryType,Microsoft.Azure.Documents.Spatial.GeometryParams)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Geometry : Microsoft.Azure.Documents.Spatial.GeometryType * Microsoft.Azure.Documents.Spatial.GeometryParams -&gt; Microsoft.Azure.Documents.Spatial.Geometry" Usage="new Microsoft.Azure.Documents.Spatial.Geometry (type, geometryParams)" />
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
        <Parameter Name="type" Type="Microsoft.Azure.Documents.Spatial.GeometryType" />
        <Parameter Name="geometryParams" Type="Microsoft.Azure.Documents.Spatial.GeometryParams" />
      </Parameters>
      <Docs>
        <param name="type">
            Geometry-Datentyp.
            </param>
        <param name="geometryParams">
            Referenz zu koordinieren System, zusätzliche Eigenschaften usw.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Geometry.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.Documents.Spatial.Geometry.AdditionalProperties" />
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
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die zusätzlichen Eigenschaften in der Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Zusätzliche Geometrieeigenschaften.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BoundingBox">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.BoundingBox BoundingBox { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Spatial.BoundingBox BoundingBox" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Geometry.BoundingBox" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BoundingBox As BoundingBox" />
      <MemberSignature Language="F#" Value="member this.BoundingBox : Microsoft.Azure.Documents.Spatial.BoundingBox" Usage="Microsoft.Azure.Documents.Spatial.Geometry.BoundingBox" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty("bbox", DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.Ignore, Order=3)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.BoundingBox</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Kontrollkästchen für diese Geometrie im Azure-Cosmos-DB-Dienst ruft des Begrenzungsrahmens.
            </summary>
        <value>
            Begrenzungsrahmen der Geometry-Instanz.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Crs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.Crs Crs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Spatial.Crs Crs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Geometry.Crs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Crs As Crs" />
      <MemberSignature Language="F#" Value="member this.Crs : Microsoft.Azure.Documents.Spatial.Crs" Usage="Microsoft.Azure.Documents.Spatial.Geometry.Crs" />
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.Crs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Referenzsystem koordinieren für diese Geometrie im Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Das koordinieren Reference System für diese Geometrie.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Geometry.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="geometry.Equals obj" />
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
            Bestimmt, ob das angegebene <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> ist gleich dem aktuellen <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> im Azure-Cosmos-DB-Dienst.
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Geometry.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="geometry.GetHashCode " />
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
            Dient als Hashfunktion für die <see cref="T:Microsoft.Azure.Documents.Spatial.Geometry" /> Typ im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Ein Hashcode für die aktuelle Geometrie.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.GeometryType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.Spatial.GeometryType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Geometry.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As GeometryType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Documents.Spatial.GeometryType" Usage="Microsoft.Azure.Documents.Spatial.Geometry.Type" />
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
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("type", Order=0, Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.GeometryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Geometrietyp im Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Geometry-Typ an.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>