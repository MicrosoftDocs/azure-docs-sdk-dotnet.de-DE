<Type Name="FabricChaosEngineException" FullName="System.Fabric.FabricChaosEngineException">
  <TypeSignature Language="C#" Value="public class FabricChaosEngineException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricChaosEngineException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricChaosEngineException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricChaosEngineException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricChaosEngineException = class&#xA;    inherit FabricException" />
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
      <para><span data-ttu-id="c1ad2-101">Die Ausnahme, die ausgelöst wird, wenn der Dienst-Fabric integrierten Chaos Test Dienst unerwartete aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-101">The exception that is thrown when Service Fabric's built-in Chaos Test service has encountered something unexpected.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricChaosEngineException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricChaosEngineException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c1ad2-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricChaosEngineException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.ChaosAlreadyRunning" />.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-102">Initializes a new instance of <see cref="T:System.Fabric.FabricChaosEngineException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.ChaosAlreadyRunning" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricChaosEngineException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricChaosEngineException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricChaosEngineException : string -&gt; System.Fabric.FabricChaosEngineException" Usage="new System.Fabric.FabricChaosEngineException message" />
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
          <para><span data-ttu-id="c1ad2-103">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-103">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="c1ad2-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricChaosEngineException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.ChaosAlreadyRunning" /> und einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-104">Initializes a new instance of <see cref="T:System.Fabric.FabricChaosEngineException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.ChaosAlreadyRunning" /> and a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricChaosEngineException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricChaosEngineException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricChaosEngineException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricChaosEngineException" Usage="new System.Fabric.FabricChaosEngineException (info, context)" />
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
          <para><span data-ttu-id="c1ad2-105">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="c1ad2-106">Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="c1ad2-107">Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-107">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="c1ad2-108">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricChaosEngineException" /> Klasse aus einem serialisierten Objekt, mit einem angegebenen Kontext.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-108">Initializes a new instance of <see cref="T:System.Fabric.FabricChaosEngineException" /> class from a serialized object data, with a specified context.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricChaosEngineException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricChaosEngineException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricChaosEngineException : string * Exception -&gt; System.Fabric.FabricChaosEngineException" Usage="new System.Fabric.FabricChaosEngineException (message, inner)" />
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
          <para><span data-ttu-id="c1ad2-109">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-109">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="c1ad2-110">Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-110">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="c1ad2-111">Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-111">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="c1ad2-112">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricChaosEngineException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="c1ad2-112">Initializes a new instance of <see cref="T:System.Fabric.FabricChaosEngineException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>