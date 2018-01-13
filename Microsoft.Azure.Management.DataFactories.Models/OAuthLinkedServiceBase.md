<Type Name="OAuthLinkedServiceBase" FullName="Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase">
  <TypeSignature Language="C#" Value="public abstract class OAuthLinkedServiceBase : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit OAuthLinkedServiceBase extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class OAuthLinkedServiceBase&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type OAuthLinkedServiceBase = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7b788-101">Die Basisklasse eines Diensts OAuth verknüpft.</span><span class="sxs-lookup"><span data-stu-id="7b788-101">Base class of an OAuth linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OAuthLinkedServiceBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7b788-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7b788-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OAuthLinkedServiceBase (string authorization, string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string authorization, string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (authorization As String, sessionId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" Usage="new Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase (authorization, sessionId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authorization" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorization">To be added.</param>
        <param name="sessionId">To be added.</param>
        <summary>
            <span data-ttu-id="7b788-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" /> Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="7b788-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public string Authorization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public Property Authorization As String" />
      <MemberSignature Language="F#" Value="member this.Authorization : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b788-104">OAuth-Autorisierung, die Zugriff auf Ressourcen in Ihrem Auftrag von ADF verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="7b788-104">OAuth authorization that may be used by ADF to access resources on your behalf.</span></span> <span data-ttu-id="7b788-105">Jede Autorisierung ist eindeutig und kann nur einmal verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="7b788-105">Each authorization is unique and may only be used once.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b788-106">OAuth-Sitzungs-ID aus der OAuth-Autorisierungssitzung.</span><span class="sxs-lookup"><span data-stu-id="7b788-106">OAuth session ID from the OAuth authorization session.</span></span>
            <span data-ttu-id="7b788-107">Jede Sitzungs-ID ist eindeutig und kann nur einmal verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="7b788-107">Each session ID is unique and may only be used once.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>