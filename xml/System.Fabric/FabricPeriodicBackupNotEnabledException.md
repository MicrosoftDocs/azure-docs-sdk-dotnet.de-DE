<Type Name="FabricPeriodicBackupNotEnabledException" FullName="System.Fabric.FabricPeriodicBackupNotEnabledException">
  <TypeSignature Language="C#" Value="public class FabricPeriodicBackupNotEnabledException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricPeriodicBackupNotEnabledException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricPeriodicBackupNotEnabledException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricPeriodicBackupNotEnabledException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricPeriodicBackupNotEnabledException = class&#xA;    inherit FabricException" />
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
            <span data-ttu-id="5308e-101">Die Ausnahme, die ausgelöst wird, die beim Sichern Planungsrichtlinie für eine Partition abrufen für die Sicherung nicht aktiviert ist</span><span class="sxs-lookup"><span data-stu-id="5308e-101">The exception that is thrown trying to get backup scheduling policy for a partition for which backup is not enabled</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricPeriodicBackupNotEnabledException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricPeriodicBackupNotEnabledException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5308e-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricPeriodicBackupNotEnabledException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5308e-102">Initializes a new instance of the <see cref="T:System.Fabric.FabricPeriodicBackupNotEnabledException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricPeriodicBackupNotEnabledException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricPeriodicBackupNotEnabledException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricPeriodicBackupNotEnabledException : string -&gt; System.Fabric.FabricPeriodicBackupNotEnabledException" Usage="new System.Fabric.FabricPeriodicBackupNotEnabledException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="5308e-103">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="5308e-103">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="5308e-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricPeriodicBackupNotEnabledException" />-Klasse mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="5308e-104">Initializes a new instance of the <see cref="T:System.Fabric.FabricPeriodicBackupNotEnabledException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricPeriodicBackupNotEnabledException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricPeriodicBackupNotEnabledException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricPeriodicBackupNotEnabledException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricPeriodicBackupNotEnabledException" Usage="new System.Fabric.FabricPeriodicBackupNotEnabledException (info, context)" />
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
        <param name="info"><span data-ttu-id="5308e-105">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" />, die die serialisierten Objektdaten für die ausgelöste Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="5308e-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> that holds the serialized object data about the exception being thrown.</span></span> </param>
        <param name="context"><span data-ttu-id="5308e-106">Der <see cref="T:System.Runtime.Serialization.StreamingContext" />, der die Kontextinformationen über die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="5308e-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span></param>
        <summary>
            <span data-ttu-id="5308e-107">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricPeriodicBackupNotEnabledException" />-Klasse mit serialisierten Daten.</span><span class="sxs-lookup"><span data-stu-id="5308e-107">Initializes a new instance of the <see cref="T:System.Fabric.FabricPeriodicBackupNotEnabledException" /> class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricPeriodicBackupNotEnabledException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricPeriodicBackupNotEnabledException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricPeriodicBackupNotEnabledException : string * Exception -&gt; System.Fabric.FabricPeriodicBackupNotEnabledException" Usage="new System.Fabric.FabricPeriodicBackupNotEnabledException (message, inner)" />
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
        <param name="message"><span data-ttu-id="5308e-108">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="5308e-108">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="5308e-109">Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="5308e-109">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="5308e-110">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricPeriodicBackupNotEnabledException" />-Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="5308e-110">Initializes a new instance of the <see cref="T:System.Fabric.FabricPeriodicBackupNotEnabledException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>