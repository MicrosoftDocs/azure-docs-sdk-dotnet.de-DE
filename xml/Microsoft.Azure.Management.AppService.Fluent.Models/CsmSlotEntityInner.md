<Type Name="CsmSlotEntityInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner">
  <TypeSignature Language="C#" Value="public class CsmSlotEntityInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CsmSlotEntityInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CsmSlotEntityInner" />
  <TypeSignature Language="F#" Value="type CsmSlotEntityInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dff16-101">Deployment-Slot-Parameter.</span><span class="sxs-lookup"><span data-stu-id="dff16-101">Deployment slot parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmSlotEntityInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dff16-102">Initialisiert eine neue Instanz der CsmSlotEntityInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dff16-102">Initializes a new instance of the CsmSlotEntityInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CsmSlotEntityInner (string targetSlot, bool preserveVnet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetSlot, bool preserveVnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetSlot As String, preserveVnet As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner : string * bool -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner (targetSlot, preserveVnet)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetSlot" Type="System.String" />
        <Parameter Name="preserveVnet" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="targetSlot"><span data-ttu-id="dff16-103">Ziel-bereitstellungsslot während Swap-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="dff16-103">Destination deployment slot during swap operation.</span></span></param>
        <param name="preserveVnet"><span data-ttu-id="dff16-104">&lt;Code&gt;"true"&lt;/code&gt; Virtuellenetzwerk in das Einschubfach während Swap; beizubehalten, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="dff16-104">&lt;code&gt;true&lt;/code&gt; to preserve Virtual Network to the slot during swap; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <summary>
            <span data-ttu-id="dff16-105">Initialisiert eine neue Instanz der CsmSlotEntityInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dff16-105">Initializes a new instance of the CsmSlotEntityInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreserveVnet">
      <MemberSignature Language="C#" Value="public bool PreserveVnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PreserveVnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.PreserveVnet" />
      <MemberSignature Language="VB.NET" Value="Public Property PreserveVnet As Boolean" />
      <MemberSignature Language="F#" Value="member this.PreserveVnet : bool with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.PreserveVnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preserveVnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dff16-106">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Virtuellenetzwerk in das Einschubfach während Swap; beizubehalten, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="dff16-106">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to preserve Virtual Network to the slot during swap; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetSlot">
      <MemberSignature Language="C#" Value="public string TargetSlot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.TargetSlot" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSlot : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.TargetSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetSlot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dff16-107">Ermittelt oder definiert Ziel bereitstellungsslot während Swap-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="dff16-107">Gets or sets destination deployment slot during swap operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CsmSlotEntityInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="csmSlotEntityInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dff16-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dff16-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dff16-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dff16-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>