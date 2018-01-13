<Type Name="ServiceGroupDescription" FullName="System.Fabric.Description.ServiceGroupDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceGroupDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupDescription" />
  <TypeSignature Language="F#" Value="type ServiceGroupDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt eine Auflistung von Informationen, erstellen und Beschreiben einer Dienstgruppe erforderlich sind.  </para>
    </summary>
    <remarks>
      <para>Eine Beschreibung der Service-Gruppe enthält eine <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> und eine Liste von Elementen in der Dienstgruppe. Die Beschreibung des Diensts sind Informationen enthalten, z. B. Metriken, Anwendungsnamen, Dienstnamen für die Gruppe und die Initialisierungsinformationen für diese Dienstgruppe. Die Liste der Elementdefinitionen werden die Dienste innerhalb der Dienstgruppe beschrieben.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServiceGroupDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupDescription (System.Fabric.Description.ServiceDescription serviceDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Description.ServiceDescription serviceDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupDescription.#ctor(System.Fabric.Description.ServiceDescription)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceGroupDescription : System.Fabric.Description.ServiceDescription -&gt; System.Fabric.Description.ServiceGroupDescription" Usage="new System.Fabric.Description.ServiceGroupDescription serviceDescription" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceDescription" Type="System.Fabric.Description.ServiceDescription" />
      </Parameters>
      <Docs>
        <param name="serviceDescription">
          <para>Die <see cref="T:System.Fabric.Description.ServiceDescription" /> verwendet als Grundlage für die <see cref="T:System.Fabric.Description.ServiceGroupDescription" />.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServiceGroupDescription" />-Klasse mit der angegebenen <see cref="T:System.Fabric.Description.ServiceDescription" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MemberDescriptions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceGroupMemberDescription&gt; MemberDescriptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServiceGroupMemberDescription&gt; MemberDescriptions" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupDescription.MemberDescriptions" />
      <MemberSignature Language="VB.NET" Value="Public Property MemberDescriptions As IList(Of ServiceGroupMemberDescription)" />
      <MemberSignature Language="F#" Value="member this.MemberDescriptions : System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceGroupMemberDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceGroupDescription.MemberDescriptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceGroupMemberDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt die Liste der <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> Objekte für die Mitglieder dieser Gruppe Dienst.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Collections.Generic.IList`1" /> vom Typ <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceDescription ServiceDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ServiceDescription ServiceDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupDescription.ServiceDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDescription As ServiceDescription" />
      <MemberSignature Language="F#" Value="member this.ServiceDescription : System.Fabric.Description.ServiceDescription with get, set" Usage="System.Fabric.Description.ServiceGroupDescription.ServiceDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Beschreibt die Dienstgruppe Dienst.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.Description.ServiceDescription" />zurück.</para>
        </value>
        <remarks>
          <para>Die Beschreibung des Diensts wird beschrieben, wie das System die Dienstgruppe, einschließlich das Partitionierungsschema, z. B. den Schlüssel, den Schlüsselbereich und andere Eigenschaften partitionieren sollten.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>