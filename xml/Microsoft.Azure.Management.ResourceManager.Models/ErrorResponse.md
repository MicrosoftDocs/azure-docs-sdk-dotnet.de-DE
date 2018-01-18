<Type Name="ErrorResponse" FullName="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse">
  <TypeSignature Language="C#" Value="public class ErrorResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ErrorResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class ErrorResponse" />
  <TypeSignature Language="F#" Value="type ErrorResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="417b2-101">Fehler Search Response – gibt an, dass ARM nicht die eingehende Anforderung verarbeitet wurde.</span><span class="sxs-lookup"><span data-stu-id="417b2-101">Error reponse indicates ARM is not able to process the incoming request.</span></span> <span data-ttu-id="417b2-102">Der Grund ist in der Fehlermeldung angegeben.</span><span class="sxs-lookup"><span data-stu-id="417b2-102">The reason is provided in the error message.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="417b2-103">Initialisiert eine neue Instanz der Klasse ErrorResponse an.</span><span class="sxs-lookup"><span data-stu-id="417b2-103">Initializes a new instance of the ErrorResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ErrorResponse (string httpStatus = null, string errorCode = null, string errorMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string httpStatus, string errorCode, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional httpStatus As String = null, Optional errorCode As String = null, Optional errorMessage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse : string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse (httpStatus, errorCode, errorMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpStatus" Type="System.String" />
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="httpStatus"><span data-ttu-id="417b2-104">HTTP-Statuscode.</span><span class="sxs-lookup"><span data-stu-id="417b2-104">Http status code.</span></span></param>
        <param name="errorCode"><span data-ttu-id="417b2-105">Fehlercode</span><span class="sxs-lookup"><span data-stu-id="417b2-105">Error code.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="417b2-106">Die Fehlermeldung, der angibt, warum der Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="417b2-106">Error message indicating why the operation failed.</span></span></param>
        <summary>
            <span data-ttu-id="417b2-107">Initialisiert eine neue Instanz der Klasse ErrorResponse an.</span><span class="sxs-lookup"><span data-stu-id="417b2-107">Initializes a new instance of the ErrorResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public string ErrorCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorCode As String" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="417b2-108">Ruft ab, oder legt ihn fest-Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="417b2-108">Gets or sets error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="417b2-109">Ruft ab oder legt die Fehlermeldung, der angibt, warum der Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="417b2-109">Gets or sets error message indicating why the operation failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatus">
      <MemberSignature Language="C#" Value="public string HttpStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.HttpStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatus As String" />
      <MemberSignature Language="F#" Value="member this.HttpStatus : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ErrorResponse.HttpStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="httpStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="417b2-110">Abrufen oder Festlegen der HTTP-Statuscode.</span><span class="sxs-lookup"><span data-stu-id="417b2-110">Gets or sets http status code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>