<Type Name="CsmUsageQuota" FullName="Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota">
  <TypeSignature Language="C#" Value="public class CsmUsageQuota" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CsmUsageQuota extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota" />
  <TypeSignature Language="VB.NET" Value="Public Class CsmUsageQuota" />
  <TypeSignature Language="F#" Value="type CsmUsageQuota = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9a0b6-101">Verwendung der das Kontingent der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-101">Usage of the quota resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmUsageQuota ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9a0b6-102">Initialisiert eine neue Instanz der CsmUsageQuota-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-102">Initializes a new instance of the CsmUsageQuota class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmUsageQuota (string unit = null, Nullable&lt;DateTime&gt; nextResetTime = null, Nullable&lt;long&gt; currentValue = null, Nullable&lt;long&gt; limit = null, Microsoft.Azure.Management.WebSites.Models.LocalizableString name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string unit, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextResetTime, valuetype System.Nullable`1&lt;int64&gt; currentValue, valuetype System.Nullable`1&lt;int64&gt; limit, class Microsoft.Azure.Management.WebSites.Models.LocalizableString name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.#ctor(System.String,System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.Azure.Management.WebSites.Models.LocalizableString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional unit As String = null, Optional nextResetTime As Nullable(Of DateTime) = null, Optional currentValue As Nullable(Of Long) = null, Optional limit As Nullable(Of Long) = null, Optional name As LocalizableString = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota : string * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.Management.WebSites.Models.LocalizableString -&gt; Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota" Usage="new Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota (unit, nextResetTime, currentValue, limit, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="nextResetTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.WebSites.Models.LocalizableString" />
      </Parameters>
      <Docs>
        <param name="unit"><span data-ttu-id="9a0b6-103">Maßeinheiten für das Kontingent Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-103">Units of measurement for the quota resourse.</span></span></param>
        <param name="nextResetTime"><span data-ttu-id="9a0b6-104">Als Nächstes Mal für die Ressource Zähler zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-104">Next reset time for the resource counter.</span></span></param>
        <param name="currentValue"><span data-ttu-id="9a0b6-105">Der aktuelle Wert des Leistungsindikators Ressource.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-105">The current value of the resource counter.</span></span></param>
        <param name="limit"><span data-ttu-id="9a0b6-106">Die Ressourcenlimit.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-106">The resource limit.</span></span></param>
        <param name="name"><span data-ttu-id="9a0b6-107">Namen des Kontingents.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-107">Quota name.</span></span></param>
        <summary>
            <span data-ttu-id="9a0b6-108">Initialisiert eine neue Instanz der CsmUsageQuota-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-108">Initializes a new instance of the CsmUsageQuota class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a0b6-109">Ruft ab oder legt den aktuellen Wert des Leistungsindikators Ressource.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-109">Gets or sets the current value of the resource counter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a0b6-110">Ruft ab oder legt das Ressourcenlimit.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-110">Gets or sets the resource limit.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.LocalizableString Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.LocalizableString Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.WebSites.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a0b6-111">Ruft ab oder legt Kontingent Namen.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-111">Gets or sets quota name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextResetTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextResetTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextResetTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.NextResetTime" />
      <MemberSignature Language="VB.NET" Value="Public Property NextResetTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextResetTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.NextResetTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextResetTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a0b6-112">Ruft ab, oder legt Sie nächsten zurücksetzen für den Leistungsindikator für die Ressource fest.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-112">Gets or sets next reset time for the resource counter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a0b6-113">Ruft ab, oder legt ihn fest Maßeinheiten für das Kontingent Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="9a0b6-113">Gets or sets units of measurement for the quota resourse.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>