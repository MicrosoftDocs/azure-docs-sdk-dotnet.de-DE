<Type Name="Snapshot" FullName="Microsoft.Azure.Management.WebSites.Models.Snapshot">
  <TypeSignature Language="C#" Value="public class Snapshot : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Snapshot extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.Snapshot" />
  <TypeSignature Language="VB.NET" Value="Public Class Snapshot&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type Snapshot = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="17f7d-101">Eine Momentaufnahme einer app.</span><span class="sxs-lookup"><span data-stu-id="17f7d-101">A snapshot of an app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Snapshot ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Snapshot.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="17f7d-102">Initialisiert eine neue Instanz der Momentaufnahme-Klasse.</span><span class="sxs-lookup"><span data-stu-id="17f7d-102">Initializes a new instance of the Snapshot class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Snapshot (string id = null, string name = null, string kind = null, string type = null, string time = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string time) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.Snapshot.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional time As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.Snapshot : string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.Snapshot" Usage="new Microsoft.Azure.Management.WebSites.Models.Snapshot (id, name, kind, type, time)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="time" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="17f7d-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="17f7d-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="17f7d-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="17f7d-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="17f7d-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="17f7d-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="17f7d-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="17f7d-106">Resource type.</span></span></param>
        <param name="time"><span data-ttu-id="17f7d-107">Die Uhrzeit, die Erstellung der Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="17f7d-107">The time the snapshot was taken.</span></span></param>
        <summary>
            <span data-ttu-id="17f7d-108">Initialisiert eine neue Instanz der Momentaufnahme-Klasse.</span><span class="sxs-lookup"><span data-stu-id="17f7d-108">Initializes a new instance of the Snapshot class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public string Time { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.Snapshot.Time" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Time As String" />
      <MemberSignature Language="F#" Value="member this.Time : string" Usage="Microsoft.Azure.Management.WebSites.Models.Snapshot.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17f7d-109">Ruft die Uhrzeit, die Erstellung der Momentaufnahme, ab.</span><span class="sxs-lookup"><span data-stu-id="17f7d-109">Gets the time the snapshot was taken.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>