<Type Name="ServiceBusException" FullName="Microsoft.Azure.ServiceBus.ServiceBusException">
  <TypeSignature Language="C#" Value="public class ServiceBusException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ServiceBusException" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type ServiceBusException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="24508-101">Basis-Ausnahme für verschiedene Service Bus-Fehler.</span><span class="sxs-lookup"><span data-stu-id="24508-101">Base Exception for various Service Bus errors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusException (bool isTransient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isTransient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusException.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isTransient As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusException : bool -&gt; Microsoft.Azure.ServiceBus.ServiceBusException" Usage="new Microsoft.Azure.ServiceBus.ServiceBusException isTransient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isTransient" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isTransient"><span data-ttu-id="24508-102">Gibt an, ob die Ausnahme flüchtig ist.</span><span class="sxs-lookup"><span data-stu-id="24508-102">Specifies whether or not the exception is transient.</span></span></param>
        <summary>
            <span data-ttu-id="24508-103">Gibt eine neue ServiceBusException</span><span class="sxs-lookup"><span data-stu-id="24508-103">Returns a new ServiceBusException</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusException (bool isTransient, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isTransient, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusException.#ctor(System.Boolean,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isTransient As Boolean, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusException : bool * Exception -&gt; Microsoft.Azure.ServiceBus.ServiceBusException" Usage="new Microsoft.Azure.ServiceBus.ServiceBusException (isTransient, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="isTransient"><span data-ttu-id="24508-104">Gibt an, ob die Ausnahme flüchtig ist.</span><span class="sxs-lookup"><span data-stu-id="24508-104">Specifies whether or not the exception is transient.</span></span></param>
        <param name="innerException"><span data-ttu-id="24508-105">Die innere Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="24508-105">The inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="24508-106">Gibt eine neue ServiceBusException</span><span class="sxs-lookup"><span data-stu-id="24508-106">Returns a new ServiceBusException</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusException (bool isTransient, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isTransient, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusException.#ctor(System.Boolean,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isTransient As Boolean, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusException : bool * string -&gt; Microsoft.Azure.ServiceBus.ServiceBusException" Usage="new Microsoft.Azure.ServiceBus.ServiceBusException (isTransient, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isTransient"><span data-ttu-id="24508-107">Gibt an, ob die Ausnahme flüchtig ist.</span><span class="sxs-lookup"><span data-stu-id="24508-107">Specifies whether or not the exception is transient.</span></span></param>
        <param name="message"><span data-ttu-id="24508-108">Die detaillierte Meldung-Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="24508-108">The detailed message exception.</span></span></param>
        <summary>
            <span data-ttu-id="24508-109">Gibt eine neue ServiceBusException</span><span class="sxs-lookup"><span data-stu-id="24508-109">Returns a new ServiceBusException</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusException (bool isTransient, string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isTransient, string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ServiceBusException.#ctor(System.Boolean,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isTransient As Boolean, message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.ServiceBusException : bool * string * Exception -&gt; Microsoft.Azure.ServiceBus.ServiceBusException" Usage="new Microsoft.Azure.ServiceBus.ServiceBusException (isTransient, message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="isTransient"><span data-ttu-id="24508-110">Gibt an, ob die Ausnahme flüchtig ist.</span><span class="sxs-lookup"><span data-stu-id="24508-110">Specifies whether or not the exception is transient.</span></span></param>
        <param name="message"><span data-ttu-id="24508-111">Die detaillierte Meldung-Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="24508-111">The detailed message exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="24508-112">Die innere Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="24508-112">The inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="24508-113">Gibt eine neue ServiceBusException</span><span class="sxs-lookup"><span data-stu-id="24508-113">Returns a new ServiceBusException</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusException.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool" Usage="Microsoft.Azure.ServiceBus.ServiceBusException.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24508-114">Ein boolescher Wert, der angibt, ob die Ausnahme ein vorübergehender Fehler ist.</span><span class="sxs-lookup"><span data-stu-id="24508-114">A boolean indicating if the exception is a transient error or not.</span></span>
            </summary>
        <value><span data-ttu-id="24508-115">Gibt "true" zurück, wenn der Benutzer den Vorgang wiederholen kann, der die Ausnahme ohne weiteren Eingriff generiert hat.</span><span class="sxs-lookup"><span data-stu-id="24508-115">returns true when user can retry the operation that generated the exception without additional intervention.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public override string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusException.Message" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.ServiceBus.ServiceBusException.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24508-116">Ruft die Nachricht als eine formatierte Zeichenfolge ab.</span><span class="sxs-lookup"><span data-stu-id="24508-116">Gets the message as a formatted string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusNamespace">
      <MemberSignature Language="C#" Value="public string ServiceBusNamespace { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ServiceBusException.ServiceBusNamespace" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceBusNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusNamespace : string" Usage="Microsoft.Azure.ServiceBus.ServiceBusException.ServiceBusNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24508-117">Ruft aus dem die Ausnahme auftrat, Service Bus-Namespace ab, sofern verfügbar.</span><span class="sxs-lookup"><span data-stu-id="24508-117">Gets the Service Bus namespace from which the exception occurred, if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>