<Type Name="TransactionFaultedException" FullName="System.Fabric.TransactionFaultedException">
  <TypeSignature Language="C#" Value="public class TransactionFaultedException : InvalidOperationException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit TransactionFaultedException extends System.InvalidOperationException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TransactionFaultedException" />
  <TypeSignature Language="VB.NET" Value="Public Class TransactionFaultedException&#xA;Inherits InvalidOperationException" />
  <TypeSignature Language="F#" Value="type TransactionFaultedException = class&#xA;    inherit InvalidOperationException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.InvalidOperationException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="6fd08-101">Die Ausnahme, die einen Fehler aufgrund der Transaktion einen Fehler verursacht intern vom System weist darauf hin.</span><span class="sxs-lookup"><span data-stu-id="6fd08-101">Exception that indicates a failure due to the transaction being faulted internally by the system.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransactionFaultedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionFaultedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.TransactionFaultedException : string -&gt; System.Fabric.TransactionFaultedException" Usage="new System.Fabric.TransactionFaultedException message" />
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
          <para><span data-ttu-id="6fd08-102">Die Fehlermeldung, in der die Ursache dieser Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="6fd08-102">The error message that explains the reason for this exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="6fd08-103">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.TransactionFaultedException" /> Klasse mit einer entsprechenden Meldung.</span><span class="sxs-lookup"><span data-stu-id="6fd08-103">Initializes a new instance of the <see cref="T:System.Fabric.TransactionFaultedException" /> class with appropriate message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransactionFaultedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionFaultedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.TransactionFaultedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.TransactionFaultedException" Usage="new System.Fabric.TransactionFaultedException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="6fd08-104">Enthält die serialisierten Objektdaten zur ausgelösten Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="6fd08-104">Contains serialized object data about the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="6fd08-105">Enthält Kontextinformationen zur Quelle bzw. zum Ziel.</span><span class="sxs-lookup"><span data-stu-id="6fd08-105">Contains contextual information about the source or destination.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="6fd08-106">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.TransactionFaultedException" /> Klasse von serialisierten Zustands.</span><span class="sxs-lookup"><span data-stu-id="6fd08-106">Initializes a new instance of the <see cref="T:System.Fabric.TransactionFaultedException" /> class from serialized state.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransactionFaultedException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionFaultedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.TransactionFaultedException : string * Exception -&gt; System.Fabric.TransactionFaultedException" Usage="new System.Fabric.TransactionFaultedException (message, inner)" />
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
        <param name="message">
          <para><span data-ttu-id="6fd08-107">Die Fehlermeldung, in der die Ursache dieser Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="6fd08-107">The error message that explains the reason for this exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="6fd08-108">Die innere Ausnahme, die detaillierte Informationen bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="6fd08-108">The Inner Exception that provides detailed information.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="6fd08-109">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.TransactionFaultedException" /> Klasse mit einer entsprechenden Meldung.</span><span class="sxs-lookup"><span data-stu-id="6fd08-109">Initializes a new instance of the <see cref="T:System.Fabric.TransactionFaultedException" /> class with appropriate message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>