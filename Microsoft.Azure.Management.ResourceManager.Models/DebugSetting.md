<Type Name="DebugSetting" FullName="Microsoft.Azure.Management.ResourceManager.Models.DebugSetting">
  <TypeSignature Language="C#" Value="public class DebugSetting" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DebugSetting extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.DebugSetting" />
  <TypeSignature Language="VB.NET" Value="Public Class DebugSetting" />
  <TypeSignature Language="F#" Value="type DebugSetting = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DebugSetting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DebugSetting.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DebugSetting-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DebugSetting (string detailLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string detailLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DebugSetting.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional detailLevel As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.DebugSetting : string -&gt; Microsoft.Azure.Management.ResourceManager.Models.DebugSetting" Usage="new Microsoft.Azure.Management.ResourceManager.Models.DebugSetting detailLevel" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="detailLevel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="detailLevel">Gibt den Typ der für das Debuggen zu protokollierenden Informationen. Die zulässigen Werte lauten "keine" RequestContent, ResponseContent, oder sowohl RequestContent und ResponseContent durch Kommas getrennt. Der Standardwert ist „none“. Überlegen Sie sich an den Typ von Informationen, die Sie während der Bereitstellung übergeben werden, beim Festlegen dieses Werts. Indem Sie Informationen über die Anforderung oder die Antwort protokollieren, machen Sie möglicherweise vertrauliche Daten verfügbar, die durch die Bereitstellungsvorgänge abgerufen werden.</param>
        <summary>
            Initialisiert eine neue Instanz der DebugSetting-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailLevel">
      <MemberSignature Language="C#" Value="public string DetailLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DetailLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DebugSetting.DetailLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailLevel As String" />
      <MemberSignature Language="F#" Value="member this.DetailLevel : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DebugSetting.DetailLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="detailLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt den Typ der für das Debuggen zu protokollierenden Informationen, ruft ab oder legt ihn fest. Die zulässigen Werte lauten "keine" RequestContent, ResponseContent, oder sowohl RequestContent und ResponseContent durch Kommas getrennt. Der Standardwert ist „none“. Überlegen Sie sich an den Typ von Informationen, die Sie während der Bereitstellung übergeben werden, beim Festlegen dieses Werts. Indem Sie Informationen über die Anforderung oder die Antwort protokollieren, machen Sie möglicherweise vertrauliche Daten verfügbar, die durch die Bereitstellungsvorgänge abgerufen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>