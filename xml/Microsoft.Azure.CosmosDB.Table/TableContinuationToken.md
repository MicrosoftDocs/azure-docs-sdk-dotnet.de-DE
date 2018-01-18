<Type Name="TableContinuationToken" FullName="Microsoft.Azure.CosmosDB.Table.TableContinuationToken">
  <TypeSignature Language="C#" Value="public sealed class TableContinuationToken : Microsoft.Azure.Storage.IContinuationToken, System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit TableContinuationToken extends System.Object implements class Microsoft.Azure.Storage.IContinuationToken, class System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableContinuationToken&#xA;Implements IContinuationToken, IXmlSerializable" />
  <TypeSignature Language="F#" Value="type TableContinuationToken = class&#xA;    interface IContinuationToken&#xA;    interface IXmlSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Storage.IContinuationToken</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Xml.Serialization.IXmlSerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Xml.Serialization.XmlRoot("ContinuationToken", IsNullable=false)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8cc6b-101">Stellt ein Fortsetzungstoken für Auflistungsvorgänge dar.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-101">Represents a continuation token for listing operations.</span></span> 
            </summary>
    <remarks><span data-ttu-id="8cc6b-102">Eine Methode, die eine Teilmenge der Ergebnisse über zurückzugeben kann ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> -Objekt gibt auch ein Fortsetzungstoken an, die in einem nachfolgenden Aufruf verwendet werden kann, um den nächsten Satz verfügbarer Ergebnisse zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-102">A method that may return a partial set of results via a <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> object also returns a continuation token, which can be used in a subsequent call to return the next set of available results.</span></span> </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableContinuationToken ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableContinuationToken.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchema">
      <MemberSignature Language="C#" Value="public System.Xml.Schema.XmlSchema GetSchema ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Xml.Schema.XmlSchema GetSchema() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableContinuationToken.GetSchema" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSchema () As XmlSchema" />
      <MemberSignature Language="F#" Value="abstract member GetSchema : unit -&gt; System.Xml.Schema.XmlSchema&#xA;override this.GetSchema : unit -&gt; System.Xml.Schema.XmlSchema" Usage="tableContinuationToken.GetSchema " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.GetSchema</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.Schema.XmlSchema</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8cc6b-103">Ruft eine XML-Darstellung eines Objekts ab.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-103">Gets an XML representation of an object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc6b-104">Ein <see cref="T:System.Xml.Schema.XmlSchema" /> zur Beschreibung der XML-Darstellung des Objekts, das von der <see cref="M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)" />-Methode erstellt und von der <see cref="M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)" />-Methode verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-104">An <see cref="T:System.Xml.Schema.XmlSchema" /> that describes the XML representation of the object that is produced by the <see cref="M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)" /> method and consumed by the <see cref="M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)" /> method.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextPartitionKey">
      <MemberSignature Language="C#" Value="public string NextPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableContinuationToken.NextPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property NextPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.NextPartitionKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableContinuationToken.NextPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cc6b-105">Ruft ab oder legt den nächsten Partitionsschlüssel für <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> enumerationsvorgängen.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-105">Gets or sets the next partition key for <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> enumeration operations.</span></span>
            </summary>
        <value><span data-ttu-id="8cc6b-106">Eine Zeichenfolge, die den nächsten Partitionsschlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-106">A string containing the next partition key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextRowKey">
      <MemberSignature Language="C#" Value="public string NextRowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextRowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableContinuationToken.NextRowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property NextRowKey As String" />
      <MemberSignature Language="F#" Value="member this.NextRowKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableContinuationToken.NextRowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cc6b-107">Ruft ab oder legt den nächsten Zeilenschlüssel für <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> enumerationsvorgängen.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-107">Gets or sets the next row key for <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> enumeration operations.</span></span>
            </summary>
        <value><span data-ttu-id="8cc6b-108">Eine Zeichenfolge, die den nächsten Zeilenschlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-108">A string containing the next row key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextTableName">
      <MemberSignature Language="C#" Value="public string NextTableName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextTableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableContinuationToken.NextTableName" />
      <MemberSignature Language="VB.NET" Value="Public Property NextTableName As String" />
      <MemberSignature Language="F#" Value="member this.NextTableName : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableContinuationToken.NextTableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cc6b-109">Ruft ab oder legt den nächsten Tabellennamen für <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> enumerationsvorgängen.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-109">Gets or sets the next table name for <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> enumeration operations.</span></span>
            </summary>
        <value><span data-ttu-id="8cc6b-110">Eine Zeichenfolge mit dem Namen des in der nächsten Tabelle.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-110">A string containing the name of the next table.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadXml">
      <MemberSignature Language="C#" Value="public void ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableContinuationToken.ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReadXml (reader As XmlReader)" />
      <MemberSignature Language="F#" Value="abstract member ReadXml : System.Xml.XmlReader -&gt; unit&#xA;override this.ReadXml : System.Xml.XmlReader -&gt; unit" Usage="tableContinuationToken.ReadXml reader" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="8cc6b-111">Die <see cref="T:System.Xml.XmlReader" /> stream, aus dem das Fortsetzungstoken deserialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-111">The <see cref="T:System.Xml.XmlReader" /> stream from which the continuation token is deserialized.</span></span></param>
        <summary>
            <span data-ttu-id="8cc6b-112">Generiert ein serialisierbares Fortsetzungstoken aus seiner XML-Darstellung.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-112">Generates a serializable continuation token from its XML representation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLocation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Storage.StorageLocation&gt; TargetLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Storage.StorageLocation&gt; TargetLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableContinuationToken.TargetLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLocation As Nullable(Of StorageLocation)" />
      <MemberSignature Language="F#" Value="member this.TargetLocation : Nullable&lt;Microsoft.Azure.Storage.StorageLocation&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableContinuationToken.TargetLocation" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IContinuationToken.TargetLocation</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Storage.StorageLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cc6b-113">Ruft ab oder legt den Speicherort an, dem das Fortsetzungstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-113">Gets or sets the storage location that the continuation token applies to.</span></span>
            </summary>
        <value><span data-ttu-id="8cc6b-114">Ein <see cref="T:Microsoft.Azure.Storage.StorageLocation" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-114">A <see cref="T:Microsoft.Azure.Storage.StorageLocation" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteXml">
      <MemberSignature Language="C#" Value="public void WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableContinuationToken.WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub WriteXml (writer As XmlWriter)" />
      <MemberSignature Language="F#" Value="abstract member WriteXml : System.Xml.XmlWriter -&gt; unit&#xA;override this.WriteXml : System.Xml.XmlWriter -&gt; unit" Usage="tableContinuationToken.WriteXml writer" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer"><span data-ttu-id="8cc6b-115">Die <see cref="T:System.Xml.XmlWriter" /> stream, in den das Fortsetzungstoken serialisiert wird.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-115">The <see cref="T:System.Xml.XmlWriter" /> stream to which the continuation token is serialized.</span></span></param>
        <summary>
            <span data-ttu-id="8cc6b-116">Konvertiert ein serialisierbares Fortsetzungstoken in seine XML-Darstellung.</span><span class="sxs-lookup"><span data-stu-id="8cc6b-116">Converts a serializable continuation token into its XML representation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>