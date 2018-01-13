<Type Name="Index" FullName="Microsoft.Azure.Documents.Index">
  <TypeSignature Language="C#" Value="public abstract class Index : Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Index extends Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Index" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Index&#xA;Inherits JsonSerializable" />
  <TypeSignature Language="F#" Value="type Index = class&#xA;    inherit JsonSerializable" />
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
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.IndexJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Basisklasse für IndexingPolicy Indizes in der Azure-Cosmos-DB-Dienst, sollten Sie einen konkrete Index z. B. HashIndex oder RangeIndex verwenden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Index (Microsoft.Azure.Documents.IndexKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Documents.IndexKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.#ctor(Microsoft.Azure.Documents.IndexKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As IndexKind)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Index : Microsoft.Azure.Documents.IndexKind -&gt; Microsoft.Azure.Documents.Index" Usage="new Microsoft.Azure.Documents.Index kind" />
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
        <Parameter Name="kind" Type="Microsoft.Azure.Documents.IndexKind" />
      </Parameters>
      <Docs>
        <param name="kind">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Index" /> Klasse für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hash">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.HashIndex Hash (Microsoft.Azure.Documents.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.HashIndex Hash(valuetype Microsoft.Azure.Documents.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Hash(Microsoft.Azure.Documents.DataType)" />
      <MemberSignature Language="F#" Value="static member Hash : Microsoft.Azure.Documents.DataType -&gt; Microsoft.Azure.Documents.HashIndex" Usage="Microsoft.Azure.Documents.Index.Hash dataType" />
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
        <ReturnType>Microsoft.Azure.Documents.HashIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
      </Parameters>
      <Docs>
        <param name="dataType">Gibt den Zieldatentyp für den Index Pfadangabe.</param>
        <summary>
            Gibt eine Instanz von der <see cref="T:Microsoft.Azure.Documents.HashIndex" /> -Klasse mit der angegebenen Datentyp für den Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>eine Instanz von <see cref="T:Microsoft.Azure.Documents.HashIndex" /> Typ.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            Hier ist ein Beispiel zum Erstellen von HashIndex-Instanz, die in den Datentyp übergeben:
            <code language="c#"><![CDATA[
            HashIndex hashIndex = Index.Hash(DataType.String);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Hash">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.HashIndex Hash (Microsoft.Azure.Documents.DataType dataType, short precision);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.HashIndex Hash(valuetype Microsoft.Azure.Documents.DataType dataType, int16 precision) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Hash(Microsoft.Azure.Documents.DataType,System.Int16)" />
      <MemberSignature Language="F#" Value="static member Hash : Microsoft.Azure.Documents.DataType * int16 -&gt; Microsoft.Azure.Documents.HashIndex" Usage="Microsoft.Azure.Documents.Index.Hash (dataType, precision)" />
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
        <ReturnType>Microsoft.Azure.Documents.HashIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
        <Parameter Name="precision" Type="System.Int16" />
      </Parameters>
      <Docs>
        <param name="dataType">Gibt den Zieldatentyp für den Index Pfadangabe.</param>
        <param name="precision">Gibt die Genauigkeit für den Datentyp dieses Index zugeordnet ist, verwendet werden.</param>
        <summary>
            Gibt eine Instanz von der <see cref="T:Microsoft.Azure.Documents.HashIndex" /> -Klasse mit der angegebenen Datentyp und die Genauigkeit für den Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>eine Instanz von <see cref="T:Microsoft.Azure.Documents.HashIndex" /> Typ.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            Hier ist ein Beispiel zum Erstellen von HashIndex-Instanz, die in den Datentyp und die Genauigkeit übergeben:
            <code language="c#"><![CDATA[
            HashIndex hashIndex = Index.Hash(DataType.String, 3);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.IndexKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.IndexKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Index.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As IndexKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.Azure.Documents.IndexKind" Usage="Microsoft.Azure.Documents.Index.Kind" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Art der Indizierung im Azure-Cosmos-DB-Dienst angewendet werden.
            </summary>
        <value>
            Einer der Werte von der <see cref="T:Microsoft.Azure.Documents.IndexKind" /> Enumeration.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Range">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.RangeIndex Range (Microsoft.Azure.Documents.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.RangeIndex Range(valuetype Microsoft.Azure.Documents.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Range(Microsoft.Azure.Documents.DataType)" />
      <MemberSignature Language="F#" Value="static member Range : Microsoft.Azure.Documents.DataType -&gt; Microsoft.Azure.Documents.RangeIndex" Usage="Microsoft.Azure.Documents.Index.Range dataType" />
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
        <ReturnType>Microsoft.Azure.Documents.RangeIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
      </Parameters>
      <Docs>
        <param name="dataType">Gibt den Zieldatentyp für den Index Pfadangabe.</param>
        <summary>
            Gibt eine Instanz von der <see cref="T:Microsoft.Azure.Documents.RangeIndex" /> -Klasse mit der angegebenen Datentyp für den Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>eine Instanz von <see cref="T:Microsoft.Azure.Documents.RangeIndex" /> Typ.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            Hier ist ein Beispiel zum Erstellen RangeIndex-Instanz, die in den Datentyp übergeben:
            <code language="c#"><![CDATA[
            RangeIndex rangeIndex = Index.Range(DataType.Number);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Range">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.RangeIndex Range (Microsoft.Azure.Documents.DataType dataType, short precision);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.RangeIndex Range(valuetype Microsoft.Azure.Documents.DataType dataType, int16 precision) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Range(Microsoft.Azure.Documents.DataType,System.Int16)" />
      <MemberSignature Language="F#" Value="static member Range : Microsoft.Azure.Documents.DataType * int16 -&gt; Microsoft.Azure.Documents.RangeIndex" Usage="Microsoft.Azure.Documents.Index.Range (dataType, precision)" />
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
        <ReturnType>Microsoft.Azure.Documents.RangeIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
        <Parameter Name="precision" Type="System.Int16" />
      </Parameters>
      <Docs>
        <param name="dataType">Gibt den Zieldatentyp für den Index Pfadangabe.</param>
        <param name="precision">Gibt die Genauigkeit für den Datentyp dieses Index zugeordnet ist, verwendet werden.</param>
        <summary>
            Gibt eine Instanz von der <see cref="T:Microsoft.Azure.Documents.RangeIndex" /> -Klasse mit der angegebenen Datentyp und die Genauigkeit für den Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>eine Instanz von <see cref="T:Microsoft.Azure.Documents.RangeIndex" /> Typ.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            Hier ist ein Beispiel zum Erstellen RangeIndex-Instanz, die in den Datentyp und die Genauigkeit übergeben:
            <code language="c#"><![CDATA[
            RangeIndex rangeIndex = Index.Range(DataType.Number, -1);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Spatial">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.SpatialIndex Spatial (Microsoft.Azure.Documents.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.SpatialIndex Spatial(valuetype Microsoft.Azure.Documents.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Spatial(Microsoft.Azure.Documents.DataType)" />
      <MemberSignature Language="F#" Value="static member Spatial : Microsoft.Azure.Documents.DataType -&gt; Microsoft.Azure.Documents.SpatialIndex" Usage="Microsoft.Azure.Documents.Index.Spatial dataType" />
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
        <ReturnType>Microsoft.Azure.Documents.SpatialIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
      </Parameters>
      <Docs>
        <param name="dataType">Gibt den Zieldatentyp für den Index Pfadangabe.</param>
        <summary>
            Gibt eine Instanz von der <see cref="T:Microsoft.Azure.Documents.SpatialIndex" /> -Klasse mit der angegebenen Datentyp für den Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>eine Instanz von <see cref="T:Microsoft.Azure.Documents.SpatialIndex" /> Typ.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            Hier ist ein Beispiel zum Erstellen von SpatialIndex-Instanz, die in den Datentyp übergeben:
            <code language="c#"><![CDATA[
            SpatialIndex spatialIndex = Index.Spatial(DataType.Point);
            ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>