<Type Name="CorsSettings" FullName="Microsoft.Azure.Management.WebSites.Models.CorsSettings">
  <TypeSignature Language="C#" Value="public class CorsSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CorsSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.CorsSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class CorsSettings" />
  <TypeSignature Language="F#" Value="type CorsSettings = class" />
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
            <span data-ttu-id="31111-101">Cross-Origin Resource Sharing (CORS)-Einstellungen für die app.</span><span class="sxs-lookup"><span data-stu-id="31111-101">Cross-Origin Resource Sharing (CORS) settings for the app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorsSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CorsSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="31111-102">Initialisiert eine neue Instanz der CorsSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="31111-102">Initializes a new instance of the CorsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorsSettings (System.Collections.Generic.IList&lt;string&gt; allowedOrigins = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; allowedOrigins) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.CorsSettings.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional allowedOrigins As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.CorsSettings : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.CorsSettings" Usage="new Microsoft.Azure.Management.WebSites.Models.CorsSettings allowedOrigins" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="allowedOrigins" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="allowedOrigins"><span data-ttu-id="31111-103">Ruft ab oder legt die Liste der Ursprünge, denen ursprungsübergreifende Aufrufe ausführen zugelassen werden soll (z. B.: http://example.com: 12345).</span><span class="sxs-lookup"><span data-stu-id="31111-103">Gets or sets the list of origins that should be allowed to make cross-origin calls (for example: http://example.com:12345).</span></span> <span data-ttu-id="31111-104">Mit „\*“ lassen Sie alle zu.</span><span class="sxs-lookup"><span data-stu-id="31111-104">Use "\*" to allow all.</span></span></param>
        <summary>
            <span data-ttu-id="31111-105">Initialisiert eine neue Instanz der CorsSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="31111-105">Initializes a new instance of the CorsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedOrigins">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedOrigins { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedOrigins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.CorsSettings.AllowedOrigins" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedOrigins As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedOrigins : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.CorsSettings.AllowedOrigins" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowedOrigins")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31111-106">Ruft ab oder legt die Liste der Ursprünge, denen ursprungsübergreifende Aufrufe ausführen zugelassen werden soll (z. B.: http://example.com: 12345).</span><span class="sxs-lookup"><span data-stu-id="31111-106">Gets or sets the list of origins that should be allowed to make cross-origin calls (for example: http://example.com:12345).</span></span> <span data-ttu-id="31111-107">Mit „\*“ lassen Sie alle zu.</span><span class="sxs-lookup"><span data-stu-id="31111-107">Use "\*" to allow all.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>