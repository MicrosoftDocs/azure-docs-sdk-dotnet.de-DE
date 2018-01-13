<Type Name="ContainerServiceCustomProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceCustomProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceCustomProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceCustomProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceCustomProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eigenschaften zum Konfigurieren eines benutzerdefinierten Container-Service-Cluster.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceCustomProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ContainerServiceCustomProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceCustomProfile (string orchestrator);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string orchestrator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (orchestrator As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile : string -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile orchestrator" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="orchestrator" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="orchestrator">Der Name der benutzerdefinierten Orchestrator verwendet werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der ContainerServiceCustomProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Orchestrator">
      <MemberSignature Language="C#" Value="public string Orchestrator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Orchestrator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.Orchestrator" />
      <MemberSignature Language="VB.NET" Value="Public Property Orchestrator As String" />
      <MemberSignature Language="F#" Value="member this.Orchestrator : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.Orchestrator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="orchestrator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der benutzerdefinierten Orchestrator verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceCustomProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceCustomProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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