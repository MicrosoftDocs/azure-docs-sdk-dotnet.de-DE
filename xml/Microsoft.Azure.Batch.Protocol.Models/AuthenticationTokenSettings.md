<Type Name="AuthenticationTokenSettings" FullName="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings">
  <TypeSignature Language="C#" Value="public class AuthenticationTokenSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthenticationTokenSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthenticationTokenSettings" />
  <TypeSignature Language="F#" Value="type AuthenticationTokenSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="33679-101">Die Einstellungen für ein Authentifizierungstoken, die die Aufgabe zum Ausführen von Batchvorgängen-Dienst verwenden können.</span><span class="sxs-lookup"><span data-stu-id="33679-101">The settings for an authentication token that the task can use to perform Batch service operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationTokenSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="33679-102">Initialisiert eine neue Instanz der AuthenticationTokenSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="33679-102">Initializes a new instance of the AuthenticationTokenSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationTokenSettings (System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; access = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; access) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.AccessScope})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional access As IList(Of AccessScope) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" Usage="new Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings access" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="access" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt;" />
      </Parameters>
      <Docs>
        <param name="access"><span data-ttu-id="33679-103">Die Batch-Ressourcen, zu denen das Token Zugriff gewährt.</span><span class="sxs-lookup"><span data-stu-id="33679-103">The Batch resources to which the token grants access.</span></span></param>
        <summary>
            <span data-ttu-id="33679-104">Initialisiert eine neue Instanz der AuthenticationTokenSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="33679-104">Initializes a new instance of the AuthenticationTokenSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As IList(Of AccessScope)" />
      <MemberSignature Language="F#" Value="member this.Access : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.AccessScope&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33679-105">Ruft ab oder legt die Batch-Ressourcen, zu denen das Token Zugriff gewährt.</span><span class="sxs-lookup"><span data-stu-id="33679-105">Gets or sets the Batch resources to which the token grants access.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="33679-106">Das Authentifizierungstoken gewährt Zugriff auf eine begrenzte Anzahl von Batch-Dienstvorgänge.</span><span class="sxs-lookup"><span data-stu-id="33679-106">The authentication token grants access to a limited set of Batch service operations.</span></span> <span data-ttu-id="33679-107">Derzeit ist der einzige unterstützte Wert für die Eigenschaft 'Auftrag', der gewährt Zugriff auf alle Vorgänge für den Auftrag, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="33679-107">Currently the only supported value for the access property is 'job', which grants access to all operations related to the job which contains the task.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>