<Type Name="FalseFilter" FullName="Microsoft.ServiceBus.Messaging.FalseFilter">
  <TypeSignature Language="C#" Value="public sealed class FalseFilter : Microsoft.ServiceBus.Messaging.SqlFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FalseFilter extends Microsoft.ServiceBus.Messaging.SqlFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.FalseFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FalseFilter&#xA;Inherits SqlFilter" />
  <TypeSignature Language="F#" Value="type FalseFilter = class&#xA;    inherit SqlFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.SqlFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="FalseFilter", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="73068-101">Stellt den Filterausdruck "false".</span><span class="sxs-lookup"><span data-stu-id="73068-101">Represents the false filter expression.</span></span></summary>
    <remarks><span data-ttu-id="73068-102">Der Ausdruck Übereinstimmung keine sollte verwendet werden, wenn Sie ein Abonnement, das anfänglich alle Nachrichten blockieren erstellen möchten.</span><span class="sxs-lookup"><span data-stu-id="73068-102">The Match None expression should be used if you want to create a subscription that initially block all messages.</span></span> <span data-ttu-id="73068-103">In der Regel ist in diesem Szenario sollten Sie das Abonnement erstellen, aber dieses Abonnement zu einem späteren Zeitpunkt aktivieren möchten.</span><span class="sxs-lookup"><span data-stu-id="73068-103">Typically in this scenario is you may want to create the subscription but want to enable this subscription at a later date.</span></span> <span data-ttu-id="73068-104">Dieser Filter wird dieses Szenario zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="73068-104">This filter will enable that scenario.</span></span> </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FalseFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="73068-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.FalseFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="73068-105">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.FalseFilter" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public override bool Match (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Match(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.Match(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Match (message As BrokeredMessage) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Match : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; bool" Usage="falseFilter.Match message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="73068-106">Die vermittelte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="73068-106">The brokered message.</span></span></param>
        <summary><span data-ttu-id="73068-107">Entspricht eine Nachricht anhand der aktuellen SQL-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="73068-107">Matches a message against the current SQL expression.</span></span></summary>
        <returns><span data-ttu-id="73068-108">"true", sofern es entspricht; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="73068-108">true if it matches; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.Filter Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.Filter Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Preprocess () As Filter" />
      <MemberSignature Language="F#" Value="override this.Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.Filter" Usage="falseFilter.Preprocess " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Filter</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="73068-109">Ruft den vorverarbeiteten Filterausdruck an.</span><span class="sxs-lookup"><span data-stu-id="73068-109">Gets the preprocessed filter expression.</span></span></summary>
        <returns><span data-ttu-id="73068-110">Der Filterausdruck vorverarbeitet.</span><span class="sxs-lookup"><span data-stu-id="73068-110">The preprocessed filter expression.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public override bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.FalseFilter.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.FalseFilter.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="73068-111">Ruft einen Wert, der angibt, ob die SQL-Filterausdruck vorverarbeitung erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="73068-111">Gets a value indicating whether the SQL filter expression requires preprocessing.</span></span></summary>
        <value><span data-ttu-id="73068-112">"true", wenn die SQL Ausdruck filtern muss vorverarbeitung; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="73068-112">true if the SQL filter expression requires preprocessing; otherwise, false.</span></span> <span data-ttu-id="73068-113">Gibt zurzeit immer "true" zurück.</span><span class="sxs-lookup"><span data-stu-id="73068-113">Currently always returns true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="falseFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="73068-114">Konvertiert die aktuelle Instanz in die Zeichenfolgendarstellung.</span><span class="sxs-lookup"><span data-stu-id="73068-114">Converts the current instance to its string representation.</span></span></summary>
        <returns><span data-ttu-id="73068-115">Eine Zeichenfolgendarstellung der aktuellen Instanz.</span><span class="sxs-lookup"><span data-stu-id="73068-115">A string representation of the current instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="falseFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="73068-116">Überprüft die SQL-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="73068-116">Validates the SQL expression.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>