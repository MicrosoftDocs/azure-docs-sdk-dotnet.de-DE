<Type Name="TableServiceEntity" FullName="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity">
  <TypeSignature Language="C#" Value="public abstract class TableServiceEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TableServiceEntity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TableServiceEntity" />
  <TypeSignature Language="F#" Value="type TableServiceEntity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Data.Services.Common.DataServiceKey(Mono.Cecil.CustomAttributeArgument[])</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ca0f3-101">Stellt eine Entität in der Windows Azure-Tabellendienst dar.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-101">Represents an entity in the Windows Azure Table service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TableServiceEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca0f3-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TableServiceEntity (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity : string * string -&gt; Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity" Usage="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity (partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="ca0f3-103">der Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-103">The partition key.</span></span></param>
        <param name="rowKey"><span data-ttu-id="ca0f3-104">Der Zeilenschlüssel.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-104">The row key.</span></span></param>
        <summary>
            <span data-ttu-id="ca0f3-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-105">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public virtual string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca0f3-106">Ruft ab oder legt den Partitionsschlüssel der einer Tabellenentität.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-106">Gets or sets the partition key of a table entity.</span></span>
            </summary>
        <value><span data-ttu-id="ca0f3-107">der Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-107">The partition key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public virtual string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity.RowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca0f3-108">Ruft ab oder legt den Zeilenschlüssel einer Entität für die Tabelle.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-108">Gets or sets the row key of a table entity.</span></span>
            </summary>
        <value><span data-ttu-id="ca0f3-109">Der Zeilenschlüssel.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-109">The row key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTime Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca0f3-110">Ruft ab oder legt den Zeitstempel der Entität fest.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-110">Gets or sets the timestamp for the entity.</span></span>
            </summary>
        <value><span data-ttu-id="ca0f3-111">Zeitstempel der Entität.</span><span class="sxs-lookup"><span data-stu-id="ca0f3-111">The entity's timestamp.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>