<Type Name="FabricCannotConnectException" FullName="System.Fabric.FabricCannotConnectException">
  <TypeSignature Language="C#" Value="public sealed class FabricCannotConnectException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit FabricCannotConnectException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricCannotConnectException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricCannotConnectException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricCannotConnectException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="fd6e9-101">Die Ausnahme, die angibt, dass CannotConnect Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="fd6e9-101">The exception that indicates that there is CannotConnect Error.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricCannotConnectException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricCannotConnectException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="fd6e9-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricCannotConnectException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.FabricCannotConnect" />.</span><span class="sxs-lookup"><span data-stu-id="fd6e9-102">Initializes a new instance of <see cref="T:System.Fabric.FabricCannotConnectException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.FabricCannotConnect" />.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricCannotConnectException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricCannotConnectException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricCannotConnectException : string -&gt; System.Fabric.FabricCannotConnectException" Usage="new System.Fabric.FabricCannotConnectException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="fd6e9-103">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="fd6e9-103">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="fd6e9-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricCannotConnectException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.FabricCannotConnect" /> und einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="fd6e9-104">Initializes a new instance of <see cref="T:System.Fabric.FabricCannotConnectException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.FabricCannotConnect" /> and a specified error message.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricCannotConnectException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricCannotConnectException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricCannotConnectException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricCannotConnectException" Usage="new System.Fabric.FabricCannotConnectException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="fd6e9-105">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="fd6e9-105">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="fd6e9-106">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="fd6e9-106">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="fd6e9-107">Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="fd6e9-107">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="fd6e9-108">Der Fehlercode, der der Ausnahme zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="fd6e9-108">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="fd6e9-109">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricCannotConnectException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="fd6e9-109">Initializes a new instance of <see cref="T:System.Fabric.FabricCannotConnectException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>