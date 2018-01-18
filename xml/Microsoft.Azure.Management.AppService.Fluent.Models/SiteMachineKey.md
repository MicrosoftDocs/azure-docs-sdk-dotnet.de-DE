<Type Name="SiteMachineKey" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey">
  <TypeSignature Language="C#" Value="public class SiteMachineKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteMachineKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteMachineKey" />
  <TypeSignature Language="F#" Value="type SiteMachineKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="809ed-101">MachineKey einer app.</span><span class="sxs-lookup"><span data-stu-id="809ed-101">MachineKey of an app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteMachineKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="809ed-102">Initialisiert eine neue Instanz der SiteMachineKey-Klasse.</span><span class="sxs-lookup"><span data-stu-id="809ed-102">Initializes a new instance of the SiteMachineKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteMachineKey (string validation = null, string validationKey = null, string decryption = null, string decryptionKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string validation, string validationKey, string decryption, string decryptionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional validation As String = null, Optional validationKey As String = null, Optional decryption As String = null, Optional decryptionKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey : string * string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey (validation, validationKey, decryption, decryptionKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="validation" Type="System.String" />
        <Parameter Name="validationKey" Type="System.String" />
        <Parameter Name="decryption" Type="System.String" />
        <Parameter Name="decryptionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="validation"><span data-ttu-id="809ed-103">MachineKey-Überprüfung.</span><span class="sxs-lookup"><span data-stu-id="809ed-103">MachineKey validation.</span></span></param>
        <param name="validationKey"><span data-ttu-id="809ed-104">Validierungsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="809ed-104">Validation key.</span></span></param>
        <param name="decryption"><span data-ttu-id="809ed-105">Entschlüsselung.</span><span class="sxs-lookup"><span data-stu-id="809ed-105">Decryption.</span></span></param>
        <param name="decryptionKey"><span data-ttu-id="809ed-106">Entschlüsselungsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="809ed-106">Decryption key.</span></span></param>
        <summary>
            <span data-ttu-id="809ed-107">Initialisiert eine neue Instanz der SiteMachineKey-Klasse.</span><span class="sxs-lookup"><span data-stu-id="809ed-107">Initializes a new instance of the SiteMachineKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Decryption">
      <MemberSignature Language="C#" Value="public string Decryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Decryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.Decryption" />
      <MemberSignature Language="VB.NET" Value="Public Property Decryption As String" />
      <MemberSignature Language="F#" Value="member this.Decryption : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.Decryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="decryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="809ed-108">Ruft ab oder legt die Entschlüsselung.</span><span class="sxs-lookup"><span data-stu-id="809ed-108">Gets or sets decryption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptionKey">
      <MemberSignature Language="C#" Value="public string DecryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DecryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.DecryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property DecryptionKey As String" />
      <MemberSignature Language="F#" Value="member this.DecryptionKey : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.DecryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="decryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="809ed-109">Ruft ab, oder legt ihn fest Entschlüsselungsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="809ed-109">Gets or sets decryption key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validation">
      <MemberSignature Language="C#" Value="public string Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property Validation As String" />
      <MemberSignature Language="F#" Value="member this.Validation : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.Validation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="validation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="809ed-110">Ruft ab, oder legt ihn fest MachineKey-Validierung.</span><span class="sxs-lookup"><span data-stu-id="809ed-110">Gets or sets machineKey validation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidationKey">
      <MemberSignature Language="C#" Value="public string ValidationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ValidationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.ValidationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidationKey As String" />
      <MemberSignature Language="F#" Value="member this.ValidationKey : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey.ValidationKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="validationKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="809ed-111">Ruft ab, oder legt ihn fest Validierungsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="809ed-111">Gets or sets validation key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>