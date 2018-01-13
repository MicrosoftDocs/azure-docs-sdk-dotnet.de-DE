<Type Name="NodeSetup" FullName="Microsoft.Azure.Management.BatchAI.Models.NodeSetup">
  <TypeSignature Language="C#" Value="public class NodeSetup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeSetup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.NodeSetup" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeSetup" />
  <TypeSignature Language="F#" Value="type NodeSetup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Hiermit können Sie den virtuellen Computer vorbereiten. Hinweis: In MountVolumes angegebenen Volumes zuerst bereitgestellt werden und dann die SetupTask ausgeführt wird. Daher kann das Setup durchzuführende Aufgabe lokalen MountPaths in der Ausführung verwenden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeSetup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der NodeSetup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeSetup (Microsoft.Azure.Management.BatchAI.Models.SetupTask setupTask = null, Microsoft.Azure.Management.BatchAI.Models.MountVolumes mountVolumes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.SetupTask setupTask, class Microsoft.Azure.Management.BatchAI.Models.MountVolumes mountVolumes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.#ctor(Microsoft.Azure.Management.BatchAI.Models.SetupTask,Microsoft.Azure.Management.BatchAI.Models.MountVolumes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.NodeSetup : Microsoft.Azure.Management.BatchAI.Models.SetupTask * Microsoft.Azure.Management.BatchAI.Models.MountVolumes -&gt; Microsoft.Azure.Management.BatchAI.Models.NodeSetup" Usage="new Microsoft.Azure.Management.BatchAI.Models.NodeSetup (setupTask, mountVolumes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="setupTask" Type="Microsoft.Azure.Management.BatchAI.Models.SetupTask" />
        <Parameter Name="mountVolumes" Type="Microsoft.Azure.Management.BatchAI.Models.MountVolumes" />
      </Parameters>
      <Docs>
        <param name="setupTask">Gibt eine Setupaufgabe, die zum Anpassen der Compute-Knoten des Clusters verwendet werden kann. Der NodeSetup Taskausführung Zählers, die ein virtuellen Computer neu gestartet wird. Aus diesem Grund muss der Code des Idempotent sein. Im Allgemeinen wird es verwendet, um entweder statische Daten herunterladen, die für alle Aufträge erforderlich ist, die für den Cluster-VMs ausführen oder Herunterladen/Installieren von Software.</param>
        <param name="mountVolumes">Informationen zu freigegebenen Volumes, die von Aufträgen verwendet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der NodeSetup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountVolumes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.MountVolumes MountVolumes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.MountVolumes MountVolumes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.MountVolumes" />
      <MemberSignature Language="VB.NET" Value="Public Property MountVolumes As MountVolumes" />
      <MemberSignature Language="F#" Value="member this.MountVolumes : Microsoft.Azure.Management.BatchAI.Models.MountVolumes with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeSetup.MountVolumes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountVolumes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.MountVolumes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest auf freigegebene Volumes von Aufträgen verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetupTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.SetupTask SetupTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.SetupTask SetupTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.SetupTask" />
      <MemberSignature Language="VB.NET" Value="Public Property SetupTask As SetupTask" />
      <MemberSignature Language="F#" Value="member this.SetupTask : Microsoft.Azure.Management.BatchAI.Models.SetupTask with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.NodeSetup.SetupTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="setupTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.SetupTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an einem setuptask der anpassen Compute-Knoten des Clusters verwendet werden kann, ruft ab oder legt ihn fest. Der NodeSetup Taskausführung Zählers, die ein virtuellen Computer neu gestartet wird. Aus diesem Grund muss der Code des Idempotent sein. Im Allgemeinen wird es verwendet, um entweder statische Daten herunterladen, die für alle Aufträge erforderlich ist, die für den Cluster-VMs ausführen oder Herunterladen/Installieren von Software.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.NodeSetup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nodeSetup.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
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