<Type Name="TwinCollectionValue" FullName="Microsoft.Azure.Devices.Shared.TwinCollectionValue">
  <TypeSignature Language="C#" Value="public class TwinCollectionValue : Newtonsoft.Json.Linq.JValue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TwinCollectionValue extends Newtonsoft.Json.Linq.JValue" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.TwinCollectionValue" />
  <TypeSignature Language="VB.NET" Value="Public Class TwinCollectionValue&#xA;Inherits JValue" />
  <TypeSignature Language="F#" Value="type TwinCollectionValue = class&#xA;    inherit JValue" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.Linq.JValue</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="923b1-101">Stellt einen Eigenschaftswert in<see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" /></span><span class="sxs-lookup"><span data-stu-id="923b1-101">Represents a property value in <see cref="T:Microsoft.Azure.Devices.Shared.TwinCollection" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetLastUpdated">
      <MemberSignature Language="C#" Value="public DateTime GetLastUpdated ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime GetLastUpdated() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollectionValue.GetLastUpdated" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLastUpdated () As DateTime" />
      <MemberSignature Language="F#" Value="member this.GetLastUpdated : unit -&gt; DateTime" Usage="twinCollectionValue.GetLastUpdated " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="923b1-102">Ruft den Zeitpunkt der letzten Aktualisierung für diese Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="923b1-102">Gets the LastUpdated time for this property</span></span>
            </summary>
        <returns><span data-ttu-id="923b1-103">DateTime-Instanz, die den Zeitpunkt der letzten Aktualisierung für diese Eigenschaft darstellt.</span><span class="sxs-lookup"><span data-stu-id="923b1-103">DateTime instance representing the LastUpdated time for this property</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLastUpdatedVersion">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; GetLastUpdatedVersion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Nullable`1&lt;int64&gt; GetLastUpdatedVersion() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollectionValue.GetLastUpdatedVersion" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLastUpdatedVersion () As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.GetLastUpdatedVersion : unit -&gt; Nullable&lt;int64&gt;" Usage="twinCollectionValue.GetLastUpdatedVersion " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="923b1-104">Ruft die LastUpdatedVersion für diese Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="923b1-104">Gets the LastUpdatedVersion for this property</span></span>
            </summary>
        <returns><span data-ttu-id="923b1-105">LastUpdatdVersion, wenn vorhanden, andernfalls null</span><span class="sxs-lookup"><span data-stu-id="923b1-105">LastUpdatdVersion if present, null otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Shared.Metadata GetMetadata ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Devices.Shared.Metadata GetMetadata() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.TwinCollectionValue.GetMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMetadata () As Metadata" />
      <MemberSignature Language="F#" Value="member this.GetMetadata : unit -&gt; Microsoft.Azure.Devices.Shared.Metadata" Usage="twinCollectionValue.GetMetadata " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.Metadata</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="923b1-106">Ruft die Metadaten für diese Eigenschaft ab.</span><span class="sxs-lookup"><span data-stu-id="923b1-106">Gets the Metadata for this property</span></span>
            </summary>
        <returns><span data-ttu-id="923b1-107">Metadaten-Instanz, die die Metadaten für diese Eigenschaft darstellt.</span><span class="sxs-lookup"><span data-stu-id="923b1-107">Metadata instance representing the metadata for this property</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public dynamic this[string propertyName] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Shared.TwinCollectionValue.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(propertyName As String) As Object" />
      <MemberSignature Language="F#" Value="member this.Item(string) : obj" Usage="Microsoft.Azure.Devices.Shared.TwinCollectionValue.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName"><span data-ttu-id="923b1-108">Name der Eigenschaft für die Suche</span><span class="sxs-lookup"><span data-stu-id="923b1-108">Property Name to lookup</span></span></param>
        <summary>
            <span data-ttu-id="923b1-109">Ruft den Wert für den angegebenen Eigenschaftennamen ab.</span><span class="sxs-lookup"><span data-stu-id="923b1-109">Gets the value for the given property name</span></span>
            </summary>
        <value><span data-ttu-id="923b1-110">Wert, falls vorhanden</span><span class="sxs-lookup"><span data-stu-id="923b1-110">Value if present</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>