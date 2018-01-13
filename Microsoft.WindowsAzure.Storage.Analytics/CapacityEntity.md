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
            Stellt eine Entität in Tabellenform Kapazität Analytics Speicher dar.
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity" />-Klasse.
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
            Ruft ab oder legt die Kapazität-Eigenschaft für die Kapazität-Entität, womit die Menge der Blob-Speicher verwendet, die für das Speicherkonto fest.
            </summary>
        <value>Ein Long-Wert, der die Menge des Blob-Speicher verwendet, die für das Speicherkonto, pro diese Kapazität Entität enthält.</value>
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
            Ruft ab oder legt die ContainerCount-Eigenschaft für die Kapazität-Entität, die die Anzahl der blobcontainer im Speicherkonto, das angibt.
            </summary>
        <value>Ein Long-Wert mit der Anzahl von Blob-Container im Speicherkonto pro diese Kapazität-Entität.</value>
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
            Ruft ab oder legt die ObjectCount-Eigenschaft für die Kapazität-Entität, die die Anzahl der und ohne Commit Blobs im Speicherkonto, das angibt.
            </summary>
        <value>Ein Long-Wert mit der Anzahl und ohne Commit Blobs im Speicherkonto pro diese Kapazität-Entität.</value>
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
            Ruft den Zeitstempel der Kapazität Entität (UTC), stellt die Startzeit für dieser Protokolleintrag ab.
            </summary>
        <value>Eine Zeichenfolge mit einem Zeitstempel in UTC.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>