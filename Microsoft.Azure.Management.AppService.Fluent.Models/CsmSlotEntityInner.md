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
            Deployment-Slot-Parameter.
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
            Initialisiert eine neue Instanz der CsmSlotEntityInner-Klasse.
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
        <param name="targetSlot">Ziel-bereitstellungsslot während Swap-Vorgang.</param>
        <param name="preserveVnet">&lt;Code&gt;"true"&lt;/code&gt; Virtuellenetzwerk in das Einschubfach während Swap; beizubehalten, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <summary>
            Initialisiert eine neue Instanz der CsmSlotEntityInner-Klasse.
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
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Virtuellenetzwerk in das Einschubfach während Swap; beizubehalten, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.
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
            Ermittelt oder definiert Ziel bereitstellungsslot während Swap-Vorgang.
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>