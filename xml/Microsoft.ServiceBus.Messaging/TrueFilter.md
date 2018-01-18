<Type Name="TrueFilter" FullName="Microsoft.ServiceBus.Messaging.TrueFilter">
  <TypeSignature Language="C#" Value="public sealed class TrueFilter : Microsoft.ServiceBus.Messaging.SqlFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TrueFilter extends Microsoft.ServiceBus.Messaging.SqlFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TrueFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TrueFilter&#xA;Inherits SqlFilter" />
  <TypeSignature Language="F#" Value="type TrueFilter = class&#xA;    inherit SqlFilter" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="TrueFilter", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="27265-101">Mit einem Filterausdruck übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="27265-101">Matches a filter expression.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TrueFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TrueFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="27265-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.TrueFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="27265-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TrueFilter" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public override bool Match (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Match(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TrueFilter.Match(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Match (message As BrokeredMessage) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Match : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; bool" Usage="trueFilter.Match message" />
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
        <param name="message"><span data-ttu-id="27265-103">Die vermittelte Nachricht.</span><span class="sxs-lookup"><span data-stu-id="27265-103">The brokered message.</span></span></param>
        <summary><span data-ttu-id="27265-104">Entspricht eine Nachricht anhand der aktuellen SQL-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="27265-104">Matches a message against the current SQL expression.</span></span></summary>
        <returns><span data-ttu-id="27265-105">"true", sofern es entspricht; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="27265-105">true if it matches; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.Filter Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.Filter Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TrueFilter.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Preprocess () As Filter" />
      <MemberSignature Language="F#" Value="override this.Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.Filter" Usage="trueFilter.Preprocess " />
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
        <summary><span data-ttu-id="27265-106">Ruft den vorverarbeiteten Filterausdruck an.</span><span class="sxs-lookup"><span data-stu-id="27265-106">Gets the preprocessed filter expression.</span></span></summary>
        <returns><span data-ttu-id="27265-107">Der Filterausdruck vorverarbeitet.</span><span class="sxs-lookup"><span data-stu-id="27265-107">The preprocessed filter expression.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public override bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TrueFilter.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.TrueFilter.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="27265-108">Ruft einen Wert, der angibt, ob die SQL-Filterausdruck vorverarbeitung erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="27265-108">Gets a value indicating whether the SQL filter expression requires preprocessing.</span></span></summary>
        <value><span data-ttu-id="27265-109">"true", wenn die SQL Ausdruck filtern muss vorverarbeitung; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="27265-109">true if the SQL filter expression requires preprocessing; otherwise, false.</span></span> <span data-ttu-id="27265-110">Gibt zurzeit immer "true" zurück.</span><span class="sxs-lookup"><span data-stu-id="27265-110">Currently always returns true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TrueFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="trueFilter.ToString " />
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
        <summary><span data-ttu-id="27265-111">Konvertiert den Wert der aktuellen Instanz in die entsprechende Zeichenfolgendarstellung.</span><span class="sxs-lookup"><span data-stu-id="27265-111">Converts the value of the current instance to its equivalent string representation.</span></span></summary>
        <returns><span data-ttu-id="27265-112">Eine Zeichenfolgendarstellung der aktuellen Instanz.</span><span class="sxs-lookup"><span data-stu-id="27265-112">A string representation of the current instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TrueFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="trueFilter.Validate " />
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
        <summary><span data-ttu-id="27265-113">Überprüft die SQL-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="27265-113">Validates the SQL expression.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>