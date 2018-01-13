<Type Name="ClusterUpgradeDeltaHealthPolicy" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy">
  <TypeSignature Language="C#" Value="public class ClusterUpgradeDeltaHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterUpgradeDeltaHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterUpgradeDeltaHealthPolicy" />
  <TypeSignature Language="F#" Value="type ClusterUpgradeDeltaHealthPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Delta-Integritätsrichtlinie für den cluster
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpgradeDeltaHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ClusterUpgradeDeltaHealthPolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpgradeDeltaHealthPolicy (int maxPercentDeltaUnhealthyNodes, int maxPercentUpgradeDomainDeltaUnhealthyNodes, int maxPercentDeltaUnhealthyApplications);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maxPercentDeltaUnhealthyNodes, int32 maxPercentUpgradeDomainDeltaUnhealthyNodes, int32 maxPercentDeltaUnhealthyApplications) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.#ctor(System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxPercentDeltaUnhealthyNodes As Integer, maxPercentUpgradeDomainDeltaUnhealthyNodes As Integer, maxPercentDeltaUnhealthyApplications As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy : int * int * int -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy (maxPercentDeltaUnhealthyNodes, maxPercentUpgradeDomainDeltaUnhealthyNodes, maxPercentDeltaUnhealthyApplications)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxPercentDeltaUnhealthyNodes" Type="System.Int32" />
        <Parameter Name="maxPercentUpgradeDomainDeltaUnhealthyNodes" Type="System.Int32" />
        <Parameter Name="maxPercentDeltaUnhealthyApplications" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxPercentDeltaUnhealthyNodes">Zusätzliche fehlerhaften Knoten in Prozent</param>
        <param name="maxPercentUpgradeDomainDeltaUnhealthyNodes">Zusätzliche fehlerhaften Knoten Prozentsatz pro upgradedomäne </param>
        <param name="maxPercentDeltaUnhealthyApplications">Zusätzliche "fehlerhaft" Anwendungen-Prozentsatz</param>
        <summary>
            Initialisiert eine neue Instanz der ClusterUpgradeDeltaHealthPolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyApplications">
      <MemberSignature Language="C#" Value="public int MaxPercentDeltaUnhealthyApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPercentDeltaUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentDeltaUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentDeltaUnhealthyApplications As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyApplications : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentDeltaUnhealthyApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxPercentDeltaUnhealthyApplications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest zusätzliche "fehlerhaft" Anwendungen-Prozentsatz
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public int MaxPercentDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentDeltaUnhealthyNodes As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyNodes : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentDeltaUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxPercentDeltaUnhealthyNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest zusätzliche fehlerhaften Knoten in Prozent
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUpgradeDomainDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public int MaxPercentUpgradeDomainDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUpgradeDomainDeltaUnhealthyNodes As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUpgradeDomainDeltaUnhealthyNodes : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxPercentUpgradeDomainDeltaUnhealthyNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt zusätzliche fehlerhaften Knoten Prozentsatz pro upgradedomäne
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clusterUpgradeDeltaHealthPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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