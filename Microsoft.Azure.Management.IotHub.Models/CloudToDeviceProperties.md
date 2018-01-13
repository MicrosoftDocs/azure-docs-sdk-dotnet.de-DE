<Type Name="CloudToDeviceProperties" FullName="Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties">
  <TypeSignature Language="C#" Value="public class CloudToDeviceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudToDeviceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudToDeviceProperties" />
  <TypeSignature Language="F#" Value="type CloudToDeviceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="783e8-101">Der IoT Hub Cloud-zu-Gerät Nachrichteneigenschaften.</span><span class="sxs-lookup"><span data-stu-id="783e8-101">The IoT hub cloud-to-device messaging properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudToDeviceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="783e8-102">Initialisiert eine neue Instanz der CloudToDeviceProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="783e8-102">Initializes a new instance of the CloudToDeviceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudToDeviceProperties (Nullable&lt;int&gt; maxDeliveryCount = null, Nullable&lt;TimeSpan&gt; defaultTtlAsIso8601 = null, Microsoft.Azure.Management.IotHub.Models.FeedbackProperties feedback = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; maxDeliveryCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; defaultTtlAsIso8601, class Microsoft.Azure.Management.IotHub.Models.FeedbackProperties feedback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties.#ctor(System.Nullable{System.Int32},System.Nullable{System.TimeSpan},Microsoft.Azure.Management.IotHub.Models.FeedbackProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxDeliveryCount As Nullable(Of Integer) = null, Optional defaultTtlAsIso8601 As Nullable(Of TimeSpan) = null, Optional feedback As FeedbackProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties : Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.Management.IotHub.Models.FeedbackProperties -&gt; Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties (maxDeliveryCount, defaultTtlAsIso8601, feedback)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxDeliveryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="defaultTtlAsIso8601" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="feedback" Type="Microsoft.Azure.Management.IotHub.Models.FeedbackProperties" />
      </Parameters>
      <Docs>
        <param name="maxDeliveryCount"><span data-ttu-id="783e8-103">Die maximale Übermittlungsanzahl für Cloud-zu-Gerät-Nachrichten in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="783e8-103">The max delivery count for cloud-to-device messages in the device queue.</span></span> <span data-ttu-id="783e8-104">Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span><span class="sxs-lookup"><span data-stu-id="783e8-104">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span></param>
        <param name="defaultTtlAsIso8601"><span data-ttu-id="783e8-105">Die Standardzeit für Cloud-zu-Gerät-Nachrichten in der Warteschlange verbleiben.</span><span class="sxs-lookup"><span data-stu-id="783e8-105">The default time to live for cloud-to-device messages in the device queue.</span></span> <span data-ttu-id="783e8-106">Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span><span class="sxs-lookup"><span data-stu-id="783e8-106">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span></param>
        <param name="feedback">To be added.</param>
        <summary>
            <span data-ttu-id="783e8-107">Initialisiert eine neue Instanz der CloudToDeviceProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="783e8-107">Initializes a new instance of the CloudToDeviceProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultTtlAsIso8601">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DefaultTtlAsIso8601 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DefaultTtlAsIso8601" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties.DefaultTtlAsIso8601" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultTtlAsIso8601 As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DefaultTtlAsIso8601 : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties.DefaultTtlAsIso8601" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultTtlAsIso8601")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="783e8-108">Ruft ab oder legt die Standardzeit für Cloud-zu-Gerät-Nachrichten in der Warteschlange verbleiben.</span><span class="sxs-lookup"><span data-stu-id="783e8-108">Gets or sets the default time to live for cloud-to-device messages in the device queue.</span></span> <span data-ttu-id="783e8-109">Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span><span class="sxs-lookup"><span data-stu-id="783e8-109">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Feedback">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.FeedbackProperties Feedback { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.FeedbackProperties Feedback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties.Feedback" />
      <MemberSignature Language="VB.NET" Value="Public Property Feedback As FeedbackProperties" />
      <MemberSignature Language="F#" Value="member this.Feedback : Microsoft.Azure.Management.IotHub.Models.FeedbackProperties with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties.Feedback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="feedback")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.FeedbackProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxDeliveryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="783e8-110">Ruft ab oder legt die maximale Übermittlungsanzahl für Cloud-zu-Gerät-Nachrichten in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="783e8-110">Gets or sets the max delivery count for cloud-to-device messages in the device queue.</span></span> <span data-ttu-id="783e8-111">Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span><span class="sxs-lookup"><span data-stu-id="783e8-111">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#cloud-to-device-messages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudToDeviceProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="783e8-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="783e8-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="783e8-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="783e8-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>