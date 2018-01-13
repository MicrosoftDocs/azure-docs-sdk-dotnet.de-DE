<Type Name="SessionStateTelemetry" FullName="Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry">
  <TypeSignature Language="C#" Value="public sealed class SessionStateTelemetry : Microsoft.ApplicationInsights.Channel.ITelemetry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SessionStateTelemetry extends System.Object implements class Microsoft.ApplicationInsights.Channel.ITelemetry" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionStateTelemetry&#xA;Implements ITelemetry" />
  <TypeSignature Language="F#" Value="type SessionStateTelemetry = class&#xA;    interface ITelemetry" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.Channel.ITelemetry</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Session state events are no longer used. This telemetry item will be sent as EventTelemetry.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="32828-101">Telemetrie-Typ verwendet, um benutzersitzungen nachzuverfolgen.</span><span class="sxs-lookup"><span data-stu-id="32828-101">Telemetry type used to track user sessions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionStateTelemetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="32828-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="32828-102">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionStateTelemetry (Microsoft.ApplicationInsights.DataContracts.SessionState state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ApplicationInsights.DataContracts.SessionState state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.#ctor(Microsoft.ApplicationInsights.DataContracts.SessionState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As SessionState)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry : Microsoft.ApplicationInsights.DataContracts.SessionState -&gt; Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry state" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.ApplicationInsights.DataContracts.SessionState" />
      </Parameters>
      <Docs>
        <param name="state">
            <span data-ttu-id="32828-103">Ein <see cref="T:Microsoft.ApplicationInsights.DataContracts.SessionState" /> Wert, der Status der benutzersitzung angibt.</span><span class="sxs-lookup"><span data-stu-id="32828-103">A <see cref="T:Microsoft.ApplicationInsights.DataContracts.SessionState" /> value indicating state of the user session.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32828-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry" />-Klasse mit der angegebenen <paramref name="state" />.</span><span class="sxs-lookup"><span data-stu-id="32828-104">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry" /> class with the specified <paramref name="state" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.Context" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Context</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.TelemetryContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="32828-105">Ruft die <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" /> der Anwendung, wenn der Sitzungsstatus aufgezeichnet wurde.</span><span class="sxs-lookup"><span data-stu-id="32828-105">Gets the <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" /> of the application when the session state was recorded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="abstract member DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry&#xA;override this.DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="sessionStateTelemetry.DeepClone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.DeepClone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetry</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize">
      <MemberSignature Language="C#" Value="void ITelemetry.Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.Microsoft#ApplicationInsights#Channel#ITelemetry#Sanitize" />
      <MemberSignature Language="VB.NET" Value="Sub Sanitize () Implements ITelemetry.Sanitize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="32828-106">Bereinigt dieser Instanz Telemetrie, um sicherzustellen, dass es vom Application Insights akzeptiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="32828-106">Sanitizes this telemetry instance to ensure it can be accepted by the Application Insights.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.Sequence" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="32828-107">Ruft ab oder legt den Wert an, der absolute Reihenfolge der Telemetrie-Elements definiert.</span><span class="sxs-lookup"><span data-stu-id="32828-107">Gets or sets the value that defines absolute order of the telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.SessionState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ApplicationInsights.DataContracts.SessionState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As SessionState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.ApplicationInsights.DataContracts.SessionState with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.SessionState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="32828-108">Ruft ab oder legt den Wert, der Status der benutzersitzung beschreiben.</span><span class="sxs-lookup"><span data-stu-id="32828-108">Gets or sets the value describing state of the user session.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.SessionStateTelemetry.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="32828-109">Ruft ab oder legt das Datum und Uhrzeit der Sitzungsstatus aufgezeichnet wurde.</span><span class="sxs-lookup"><span data-stu-id="32828-109">Gets or sets the date and time the session state was recorded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>