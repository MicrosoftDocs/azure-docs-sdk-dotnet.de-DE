<Type Name="Error" FullName="Microsoft.Azure.KeyVault.Models.Error">
  <TypeSignature Language="C#" Value="public class Error" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Error extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.Error" />
  <TypeSignature Language="VB.NET" Value="Public Class Error" />
  <TypeSignature Language="F#" Value="type Error = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ce08d-101">Die schlüsseltresor-Serverfehler.</span><span class="sxs-lookup"><span data-stu-id="ce08d-101">The key vault server error.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Error ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Error.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ce08d-102">Initialisiert eine neue Instanz der Error-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ce08d-102">Initializes a new instance of the Error class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Error (string code = null, string message = null, Microsoft.Azure.KeyVault.Models.Error innerError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, class Microsoft.Azure.KeyVault.Models.Error innerError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Error.#ctor(System.String,System.String,Microsoft.Azure.KeyVault.Models.Error)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional innerError As Error = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.Error : string * string * Microsoft.Azure.KeyVault.Models.Error -&gt; Microsoft.Azure.KeyVault.Models.Error" Usage="new Microsoft.Azure.KeyVault.Models.Error (code, message, innerError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerError" Type="Microsoft.Azure.KeyVault.Models.Error" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="ce08d-103">Der Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="ce08d-103">The error code.</span></span></param>
        <param name="message"><span data-ttu-id="ce08d-104">Die Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="ce08d-104">The error message.</span></span></param>
        <param name="innerError">To be added.</param>
        <summary>
            <span data-ttu-id="ce08d-105">Initialisiert eine neue Instanz der Error-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ce08d-105">Initializes a new instance of the Error class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Error.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.KeyVault.Models.Error.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce08d-106">Ruft den Fehlercode ab.</span><span class="sxs-lookup"><span data-stu-id="ce08d-106">Gets the error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InnerError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.Error InnerError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.Error InnerError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Error.InnerError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InnerError As Error" />
      <MemberSignature Language="F#" Value="member this.InnerError : Microsoft.Azure.KeyVault.Models.Error" Usage="Microsoft.Azure.KeyVault.Models.Error.InnerError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="innererror")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.Error</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Error.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.KeyVault.Models.Error.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce08d-107">Ruft die Fehlermeldung ab.</span><span class="sxs-lookup"><span data-stu-id="ce08d-107">Gets the error message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>