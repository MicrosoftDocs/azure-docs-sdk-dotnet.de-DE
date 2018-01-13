<Type Name="IpAddress" FullName="Microsoft.Azure.Management.ContainerInstance.Models.IpAddress">
  <TypeSignature Language="C#" Value="public class IpAddress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi IpAddress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.IpAddress" />
  <TypeSignature Language="VB.NET" Value="Public Class IpAddress" />
  <TypeSignature Language="F#" Value="type IpAddress = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            IP-Adresse für die Containergruppe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.IpAddress.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse IP-Adresse an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpAddress (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Port&gt; ports, string ip = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Port&gt; ports, string ip) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.IpAddress.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.ContainerInstance.Models.Port},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ports As IList(Of Port), Optional ip As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.IpAddress : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Port&gt; * string -&gt; Microsoft.Azure.Management.ContainerInstance.Models.IpAddress" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.IpAddress (ports, ip)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ports" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Port&gt;" />
        <Parameter Name="ip" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ports">Die Liste der Ports, die für die Containergruppe verfügbar gemacht werden.</param>
        <param name="ip">Die IP-Adresse für das öffentliche Internet verfügbar gemacht.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse IP-Adresse an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ip">
      <MemberSignature Language="C#" Value="public string Ip { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Ip" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.IpAddress.Ip" />
      <MemberSignature Language="VB.NET" Value="Public Property Ip As String" />
      <MemberSignature Language="F#" Value="member this.Ip : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.IpAddress.Ip" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ip")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die IP-Adresse für das öffentliche Internet verfügbar gemacht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ports">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Port&gt; Ports { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Port&gt; Ports" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.IpAddress.Ports" />
      <MemberSignature Language="VB.NET" Value="Public Property Ports As IList(Of Port)" />
      <MemberSignature Language="F#" Value="member this.Ports : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Port&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.IpAddress.Ports" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ports")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ContainerInstance.Models.Port&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Ports, die für die Containergruppe verfügbar gemacht werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public static string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.IpAddress.Type" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ContainerInstance.Models.IpAddress.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob die IP-Adresse für das öffentliche Internet verfügbar gemacht wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.IpAddress.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="ipAddress.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
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