<Type Name="FabricInvalidPartitionSelectorException" FullName="System.Fabric.FabricInvalidPartitionSelectorException">
  <TypeSignature Language="C#" Value="public class FabricInvalidPartitionSelectorException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricInvalidPartitionSelectorException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricInvalidPartitionSelectorException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricInvalidPartitionSelectorException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricInvalidPartitionSelectorException = class&#xA;    inherit FabricException" />
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
            <span data-ttu-id="8220c-101">Die Ausnahme, die ausgelöst wird, wenn eine PartitionSelector ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="8220c-101">The exception that is thrown when a PartitionSelector is invalid.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidPartitionSelectorException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidPartitionSelectorException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8220c-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricInvalidPartitionSelectorException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8220c-102">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidPartitionSelectorException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidPartitionSelectorException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidPartitionSelectorException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidPartitionSelectorException : string -&gt; System.Fabric.FabricInvalidPartitionSelectorException" Usage="new System.Fabric.FabricInvalidPartitionSelectorException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="8220c-103">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="8220c-103">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="8220c-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricInvalidPartitionSelectorException" />-Klasse mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="8220c-104">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidPartitionSelectorException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidPartitionSelectorException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidPartitionSelectorException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidPartitionSelectorException : string * Exception -&gt; System.Fabric.FabricInvalidPartitionSelectorException" Usage="new System.Fabric.FabricInvalidPartitionSelectorException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="8220c-105">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="8220c-105">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="8220c-106">Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="8220c-106">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="8220c-107">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricInvalidPartitionSelectorException" />-Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="8220c-107">Initializes a new instance of the <see cref="T:System.Fabric.FabricInvalidPartitionSelectorException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricInvalidPartitionSelectorException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricInvalidPartitionSelectorException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricInvalidPartitionSelectorException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricInvalidPartitionSelectorException" Usage="new System.Fabric.FabricInvalidPartitionSelectorException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="8220c-108">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="8220c-108">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para>
            <span data-ttu-id="8220c-109"><see cref="T:System.Fabric.FabricErrorCode" />definiert den Fehlercode, dem die Ausnahme, um fließt ist.</span><span class="sxs-lookup"><span data-stu-id="8220c-109"><see cref="T:System.Fabric.FabricErrorCode" /> defines the error code that the exception is wrapping around.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8220c-110">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricInvalidPartitionSelectorException" /> mit angegebenen Nachricht und Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="8220c-110">Initializes a new instance of <see cref="T:System.Fabric.FabricInvalidPartitionSelectorException" /> with specified message and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>