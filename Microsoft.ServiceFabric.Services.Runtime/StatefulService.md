<Type Name="StatefulService" FullName="Microsoft.ServiceFabric.Services.Runtime.StatefulService">
  <TypeSignature Language="C#" Value="public abstract class StatefulService : Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit StatefulService extends Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.StatefulService" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class StatefulService&#xA;Inherits StatefulServiceBase" />
  <TypeSignature Language="F#" Value="type StatefulService = class&#xA;    inherit StatefulServiceBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die Basisklasse dar, für Microsoft Service Fabric-basierte statusbehaftete zuverlässige Dienst die bietet eine <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> Zustand des Diensts verwalten. Ableiten von dieser Klasse zum Implementieren eines Microsoft Service Fabric-basierten statusbehafteten zuverlässige-Diensts.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatefulService (System.Fabric.StatefulServiceContext serviceContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulService.#ctor(System.Fabric.StatefulServiceContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatefulServiceContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatefulService : System.Fabric.StatefulServiceContext -&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulService" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatefulService serviceContext" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            Ein <see cref="T:System.Fabric.StatefulServiceContext" /> beschreibt den Kontext, einem zustandsbehafteten Dienst, der er Informationen wie Replikat-ID, Partitions-ID und Name des Diensts bereitstellt.
            </param>
        <summary>
            Erstellt ein neues <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulService" /> Standardwert <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />: <see cref="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatefulService (System.Fabric.StatefulServiceContext serviceContext, Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2 reliableStateManagerReplica);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext, class Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2 reliableStateManagerReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatefulService.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatefulServiceContext, reliableStateManagerReplica As IReliableStateManagerReplica2)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatefulService : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2 -&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulService" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatefulService (serviceContext, reliableStateManagerReplica)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="reliableStateManagerReplica" Type="Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            Ein <see cref="T:System.Fabric.StatefulServiceContext" /> beschreibt den Kontext, einem zustandsbehafteten Dienst, der er Informationen wie Replikat-ID, Partitions-ID und Name des Diensts bereitstellt.
            </param>
        <param name="reliableStateManagerReplica">
            Ein <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2" /> einem zuverlässigen Zustand Anbieter Replikat darstellt.
            </param>
        <summary>
            Erstellt einen neuen zustandsbehafteten Dienst. Überschreiben Sie diese Methode, um einen neuen zustandsbehaftete Dienst mit nicht standardmäßigen Status-Manager-Replikat zu erstellen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateManager">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.IReliableStateManager StateManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Data.IReliableStateManager StateManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatefulService.StateManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateManager As IReliableStateManager" />
      <MemberSignature Language="F#" Value="member this.StateManager : Microsoft.ServiceFabric.Data.IReliableStateManager" Usage="Microsoft.ServiceFabric.Services.Runtime.StatefulService.StateManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.IReliableStateManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft dieses Replikats <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.
            </summary>
        <value>Die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> des Replikats.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>