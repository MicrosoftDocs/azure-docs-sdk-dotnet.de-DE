<Type Name="CapacityEntity" FullName="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity">
  <TypeSignature Language="C#" Value="public class CapacityEntity : Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CapacityEntity extends Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class CapacityEntity&#xA;Inherits TableEntity" />
  <TypeSignature Language="F#" Value="type CapacityEntity = class&#xA;    inherit TableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Table.TableEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="af7a8-101">Stellt eine Entität in Tabellenform Kapazität Analytics Speicher dar.</span><span class="sxs-lookup"><span data-stu-id="af7a8-101">Represents an entity in a storage analytics capacity table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CapacityEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="af7a8-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="af7a8-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public long Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Long" />
      <MemberSignature Language="F#" Value="member this.Capacity : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af7a8-103">Ruft ab oder legt die Kapazität-Eigenschaft für die Kapazität-Entität, womit die Menge der Blob-Speicher verwendet, die für das Speicherkonto fest.</span><span class="sxs-lookup"><span data-stu-id="af7a8-103">Gets or sets the Capacity property for capacity entity, which indicates the quantity of Blob storage used by the storage account.</span></span>
            </summary>
        <value><span data-ttu-id="af7a8-104">Ein Long-Wert, der die Menge des Blob-Speicher verwendet, die für das Speicherkonto, pro diese Kapazität Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="af7a8-104">A long containing the quantity of Blob storage used by the storage account, per this capacity entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerCount">
      <MemberSignature Language="C#" Value="public long ContainerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ContainerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.ContainerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerCount As Long" />
      <MemberSignature Language="F#" Value="member this.ContainerCount : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.ContainerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af7a8-105">Ruft ab oder legt die ContainerCount-Eigenschaft für die Kapazität-Entität, die die Anzahl der blobcontainer im Speicherkonto, das angibt.</span><span class="sxs-lookup"><span data-stu-id="af7a8-105">Gets or sets the ContainerCount property for the capacity entity, which indicates the number of blob containers in the storage account.</span></span>
            </summary>
        <value><span data-ttu-id="af7a8-106">Ein Long-Wert mit der Anzahl von Blob-Container im Speicherkonto pro diese Kapazität-Entität.</span><span class="sxs-lookup"><span data-stu-id="af7a8-106">A long containing the number of blob containers in the storage account, per this capacity entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectCount">
      <MemberSignature Language="C#" Value="public long ObjectCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ObjectCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.ObjectCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectCount As Long" />
      <MemberSignature Language="F#" Value="member this.ObjectCount : int64 with get, set" Usage="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.ObjectCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af7a8-107">Ruft ab oder legt die ObjectCount-Eigenschaft für die Kapazität-Entität, die die Anzahl der und ohne Commit Blobs im Speicherkonto, das angibt.</span><span class="sxs-lookup"><span data-stu-id="af7a8-107">Gets or sets the ObjectCount property for the capacity entity, which indicates the number of committed and uncommitted blobs in the storage account.</span></span>
            </summary>
        <value><span data-ttu-id="af7a8-108">Ein Long-Wert mit der Anzahl und ohne Commit Blobs im Speicherkonto pro diese Kapazität-Entität.</span><span class="sxs-lookup"><span data-stu-id="af7a8-108">A long containing the number of committed and uncommitted blobs in the storage account, per this capacity entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public DateTimeOffset Time { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.Time" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Time As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Time : DateTimeOffset" Usage="Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af7a8-109">Ruft den Zeitstempel der Kapazität Entität (UTC), stellt die Startzeit für dieser Protokolleintrag ab.</span><span class="sxs-lookup"><span data-stu-id="af7a8-109">Gets the capacity entity's timestamp in UTC, representing the start time for that log entry.</span></span>
            </summary>
        <value><span data-ttu-id="af7a8-110">Eine Zeichenfolge mit einem Zeitstempel in UTC.</span><span class="sxs-lookup"><span data-stu-id="af7a8-110">A string containing a timestamp in UTC.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>