<Type Name="ValidateResponse" FullName="Microsoft.Azure.Management.WebSites.Models.ValidateResponse">
  <TypeSignature Language="C#" Value="public class ValidateResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValidateResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ValidateResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class ValidateResponse" />
  <TypeSignature Language="F#" Value="type ValidateResponse = class" />
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
            <span data-ttu-id="558ed-101">Beschreibt das Ergebnis der Überprüfung der Ressource.</span><span class="sxs-lookup"><span data-stu-id="558ed-101">Describes the result of resource validation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ValidateResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="558ed-102">Initialisiert eine neue Instanz der ValidateResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="558ed-102">Initializes a new instance of the ValidateResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateResponse (string status = null, Microsoft.Azure.Management.WebSites.Models.ValidateResponseError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, class Microsoft.Azure.Management.WebSites.Models.ValidateResponseError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ValidateResponse.#ctor(System.String,Microsoft.Azure.Management.WebSites.Models.ValidateResponseError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As String = null, Optional error As ValidateResponseError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ValidateResponse : string * Microsoft.Azure.Management.WebSites.Models.ValidateResponseError -&gt; Microsoft.Azure.Management.WebSites.Models.ValidateResponse" Usage="new Microsoft.Azure.Management.WebSites.Models.ValidateResponse (status, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.WebSites.Models.ValidateResponseError" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="558ed-103">Ergebnis der Überprüfung.</span><span class="sxs-lookup"><span data-stu-id="558ed-103">Result of validation.</span></span></param>
        <param name="error"><span data-ttu-id="558ed-104">Fehlerdetails für den Fall, wenn die Validierung fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="558ed-104">Error details for the case when validation fails.</span></span></param>
        <summary>
            <span data-ttu-id="558ed-105">Initialisiert eine neue Instanz der ValidateResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="558ed-105">Initializes a new instance of the ValidateResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.ValidateResponseError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.ValidateResponseError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateResponse.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As ValidateResponseError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.WebSites.Models.ValidateResponseError with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateResponse.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ValidateResponseError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="558ed-106">Ermittelt oder definiert Fehlerdetails für den Fall, wenn die Validierung fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="558ed-106">Gets or sets error details for the case when validation fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateResponse.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateResponse.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="558ed-107">Ruft ab, oder legt ihn fest Ergebnis der Überprüfung.</span><span class="sxs-lookup"><span data-stu-id="558ed-107">Gets or sets result of validation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>