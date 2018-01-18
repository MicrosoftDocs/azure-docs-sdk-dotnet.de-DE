<Type Name="OperationRetrySettings" FullName="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings">
  <TypeSignature Language="C#" Value="public sealed class OperationRetrySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OperationRetrySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OperationRetrySettings" />
  <TypeSignature Language="F#" Value="type OperationRetrySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="53c41-101">Gibt die Richtlinie für Wiederholungsversuche von Anforderungen auf Ausnahmen in den Kommunikationskanal zwischen Client und Dienst Replikate.</span><span class="sxs-lookup"><span data-stu-id="53c41-101">Specifies the policy for retrying requests on exceptions in the communication channel between client and service replicas.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationRetrySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="53c41-102">Instanziiert OperationRetrySettings mit Standardwerten für die wiederholungseinstellungen an.</span><span class="sxs-lookup"><span data-stu-id="53c41-102">Instantiates OperationRetrySettings with default values for the retry settings.</span></span>
            <span data-ttu-id="53c41-103">Die Standardwerte für MaxRetryBackoffIntervalOnTransientErrors NonTransientErrors sind 2 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="53c41-103">The default values for MaxRetryBackoffIntervalOnTransientErrors, NonTransientErrors are 2 seconds.</span></span> <span data-ttu-id="53c41-104">Der Standardwert für MaxRetryCount ist 10.</span><span class="sxs-lookup"><span data-stu-id="53c41-104">The default value for MaxRetryCount is 10.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationRetrySettings (TimeSpan maxRetryBackoffIntervalOnTransientErrors, TimeSpan maxRetryBackoffIntervalOnNonTransientErrors, int defaultMaxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxRetryBackoffIntervalOnTransientErrors, valuetype System.TimeSpan maxRetryBackoffIntervalOnNonTransientErrors, int32 defaultMaxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.#ctor(System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxRetryBackoffIntervalOnTransientErrors As TimeSpan, maxRetryBackoffIntervalOnNonTransientErrors As TimeSpan, defaultMaxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings : TimeSpan * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings (maxRetryBackoffIntervalOnTransientErrors, maxRetryBackoffIntervalOnNonTransientErrors, defaultMaxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxRetryBackoffIntervalOnTransientErrors" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffIntervalOnNonTransientErrors" Type="System.TimeSpan" />
        <Parameter Name="defaultMaxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxRetryBackoffIntervalOnTransientErrors">
            <span data-ttu-id="53c41-105">Gibt das maximale Zeitintervall, Backoff vor der Wiederholung zuzulassen, falls der vorübergehenden Fehler</span><span class="sxs-lookup"><span data-stu-id="53c41-105">Specifies the maximum interval to back-off before retrying incase of Transient errors</span></span>
            </param>
        <param name="maxRetryBackoffIntervalOnNonTransientErrors">
            <span data-ttu-id="53c41-106">Gibt das maximale Zeitintervall zu Backoff vor der Wiederholung zuzulassen, falls der nicht vorübergehende Fehler</span><span class="sxs-lookup"><span data-stu-id="53c41-106">Specifies the maximum interval to back-off before retrying incase of Non transient errors</span></span>
            </param>
        <param name="defaultMaxRetryCount">
            <span data-ttu-id="53c41-107">Gibt die maximale Anzahl der Wiederholungsversuche an.</span><span class="sxs-lookup"><span data-stu-id="53c41-107">Specifies the maximum number of times to retry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="53c41-108">Instanziiert OperationRetrySettings mit den angegebenen Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="53c41-108">Instantiates OperationRetrySettings with the supplied settings.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMaxRetryCount">
      <MemberSignature Language="C#" Value="public int DefaultMaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DefaultMaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.DefaultMaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultMaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DefaultMaxRetryCount : int" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.DefaultMaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53c41-109">Gibt die maximale Anzahl der Wiederholungsversuche an.</span><span class="sxs-lookup"><span data-stu-id="53c41-109">Specifies the maximum number of times to retry.</span></span>
            </summary>
        <value><span data-ttu-id="53c41-110">Maximale Anzahl der Wiederholungsversuche eine bestimmte Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="53c41-110">Maximum number of times to retry a specific exception.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryBackoffIntervalOnNonTransientErrors">
      <MemberSignature Language="C#" Value="public TimeSpan MaxRetryBackoffIntervalOnNonTransientErrors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxRetryBackoffIntervalOnNonTransientErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnNonTransientErrors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryBackoffIntervalOnNonTransientErrors As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxRetryBackoffIntervalOnNonTransientErrors : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnNonTransientErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53c41-111">Gibt das maximale Zeitintervall, und wiederholen Sie dann im Fall von vorübergehenden Fehlern nicht Backoff</span><span class="sxs-lookup"><span data-stu-id="53c41-111">Specifies the maximum interval to back-off before retrying in-case of Non transient errors</span></span>
            </summary>
        <value><span data-ttu-id="53c41-112">Maximales Wiederholungsintervall auf Backoff auf nicht vorübergehende Fehler</span><span class="sxs-lookup"><span data-stu-id="53c41-112">Maximum retry interval to back-off on non transient errors</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryBackoffIntervalOnTransientErrors">
      <MemberSignature Language="C#" Value="public TimeSpan MaxRetryBackoffIntervalOnTransientErrors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxRetryBackoffIntervalOnTransientErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryBackoffIntervalOnTransientErrors As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxRetryBackoffIntervalOnTransientErrors : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53c41-113">Gibt das maximale Zeitintervall, und wiederholen Sie dann im Fall von vorübergehenden Fehlern Backoff</span><span class="sxs-lookup"><span data-stu-id="53c41-113">Specifies the maximum interval to back-off before retrying in-case of Transient errors</span></span>
            </summary>
        <value><span data-ttu-id="53c41-114">Maximales Wiederholungsintervall auf Backoff auf vorübergehende Fehler</span><span class="sxs-lookup"><span data-stu-id="53c41-114">Maximum retry interval to back-off on transient errors</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>