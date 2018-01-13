<Type Name="HashIndex" FullName="Microsoft.Azure.Documents.HashIndex">
  <TypeSignature Language="C#" Value="public sealed class HashIndex : Microsoft.Azure.Documents.Index, ICloneable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HashIndex extends Microsoft.Azure.Documents.Index implements class System.ICloneable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.HashIndex" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HashIndex&#xA;Inherits Index&#xA;Implements ICloneable" />
  <TypeSignature Language="F#" Value="type HashIndex = class&#xA;    inherit Index&#xA;    interface ICloneable" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Index</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ICloneable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt Details der Einstellung für die Hash-Index in einem Azure-Cosmos-DB-Dienst dar.
            </summary>
    <remarks>
            Kann verwendet werden, um Abfragen wie dienen: Wählen Sie * aus Docs d WHERE d.prop = 5.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashIndex (Microsoft.Azure.Documents.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Documents.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.HashIndex.#ctor(Microsoft.Azure.Documents.DataType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.HashIndex : Microsoft.Azure.Documents.DataType -&gt; Microsoft.Azure.Documents.HashIndex" Usage="new Microsoft.Azure.Documents.HashIndex dataType" />
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
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
      </Parameters>
      <Docs>
        <param name="dataType">Gibt den Zieldatentyp für den Index Pfadangabe.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.HashIndex" /> -Klasse mit der angegebenen Datentyp für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="P:Microsoft.Azure.Documents.HashIndex.DataType" />
        <example>
            Hier ist ein Beispiel zum Instanziieren von HashIndex-Klasse, die in den Datentyp übergeben:
            <code language="c#"><![CDATA[
            HashIndex hashIndex = new HashIndex(DataType.String);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashIndex (Microsoft.Azure.Documents.DataType dataType, short precision);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Documents.DataType dataType, int16 precision) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.HashIndex.#ctor(Microsoft.Azure.Documents.DataType,System.Int16)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.HashIndex : Microsoft.Azure.Documents.DataType * int16 -&gt; Microsoft.Azure.Documents.HashIndex" Usage="new Microsoft.Azure.Documents.HashIndex (dataType, precision)" />
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
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
        <Parameter Name="precision" Type="System.Int16" />
      </Parameters>
      <Docs>
        <param name="dataType">Gibt den Zieldatentyp für den Index Pfadangabe.</param>
        <param name="precision">Gibt die Genauigkeit für den Datentyp dieses Index zugeordnet ist, verwendet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.HashIndex" /> Klasse mit der angegebenen Datentyp und Genauigkeit für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="P:Microsoft.Azure.Documents.HashIndex.DataType" />
        <example>
            Hier ist ein Beispiel zum Instanziieren von HashIndex-Klasse, die in den Datentyp und die Genauigkeit übergeben:
            <code language="c#"><![CDATA[
            HashIndex hashIndex = new HashIndex(DataType.String, 3);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.HashIndex.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="hashIndex.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ICloneable.Clone</InterfaceMember>
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Kopie der Hash-Index für den Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>Ein Klon des hashindexes.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.DataType DataType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.DataType DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.HashIndex.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Property DataType As DataType" />
      <MemberSignature Language="F#" Value="member this.DataType : Microsoft.Azure.Documents.DataType with get, set" Usage="Microsoft.Azure.Documents.HashIndex.DataType" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie den Datentyp für den diesen Index angewendet werden soll im Azure-Cosmos-DB-Dienst fest.
            </summary>
        <value>
            Der Datentyp für den diesen Index angewendet werden soll.
            </value>
        <remarks>Verweisen auf <a href="http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy">Richtlinie für die Indizierung einer Auflistung anzupassen</a> für gültige Wertebereiche.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Precision">
      <MemberSignature Language="C#" Value="public Nullable&lt;short&gt; Precision { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int16&gt; Precision" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.HashIndex.Precision" />
      <MemberSignature Language="VB.NET" Value="Public Property Precision As Nullable(Of Short)" />
      <MemberSignature Language="F#" Value="member this.Precision : Nullable&lt;int16&gt; with get, set" Usage="Microsoft.Azure.Documents.HashIndex.Precision" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="precision")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int16&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Genauigkeit für diesen bestimmten Index in der Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Die Genauigkeit für diesen bestimmten Index. Gibt null, wenn nichts anderes festgelegt.
            </value>
        <remarks>Verweisen auf <a href="http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy">Richtlinie für die Indizierung einer Auflistung anzupassen</a> für gültige Wertebereiche.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>