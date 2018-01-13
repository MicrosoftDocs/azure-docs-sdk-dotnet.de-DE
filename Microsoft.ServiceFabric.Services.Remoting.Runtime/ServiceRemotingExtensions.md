<Type Name="ServiceRemotingExtensions" FullName="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions">
  <TypeSignature Language="C#" Value="public static class ServiceRemotingExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceRemotingExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServiceRemotingExtensions" />
  <TypeSignature Language="F#" Value="type ServiceRemotingExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diese Klasse fügt Erweiterungsmethoden zum Erstellen <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für Remoting-Methoden von der Dienstschnittstellen die von der abgeleiteten <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> Schnittstelle.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceRemotingInstanceListeners&lt;TStatelessService&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceRemotingInstanceListeners&lt;TStatelessService&gt; (this TStatelessService serviceImplementation) where TStatelessService : Microsoft.ServiceFabric.Services.Runtime.StatelessService, Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceRemotingInstanceListeners&lt;(class Microsoft.ServiceFabric.Services.Runtime.StatelessService, class Microsoft.ServiceFabric.Services.Remoting.IService) TStatelessService&gt;(!!TStatelessService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingInstanceListeners``1(``0)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateServiceRemotingInstanceListeners(Of TStatelessService As {StatelessService, IService}) (serviceImplementation As TStatelessService) As IEnumerable(Of ServiceInstanceListener)" />
      <MemberSignature Language="F#" Value="static member CreateServiceRemotingInstanceListeners : 'StatelessService -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; (requires 'StatelessService :&gt; Microsoft.ServiceFabric.Services.Runtime.StatelessService and 'StatelessService :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingInstanceListeners serviceImplementation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TStatelessService">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatelessService</BaseTypeName>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceImplementation" Type="TStatelessService" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="TStatelessService">Geben Sie die Einschränkung für die Dienst-Implementierung. Die dienstimplementierung muss abgeleitet <see cref="T:System.Fabric.Query.StatelessService" /> und eine oder mehrere Schnittstellen implementiert, die Ableitung <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> Schnittstelle.</typeparam>
        <param name="serviceImplementation">Eine zustandslose dienstimplementierung.</param>
        <summary>
            Eine Erweiterungsmethode, die erstellt eine <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für die Implementierung eines zustandslosen Diensts.
            </summary>
        <returns>Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> Kommunikation Listener diese Datenbanken die Schnittstellen abgeleitet <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> Schnittstelle.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener&lt;TStatefulService&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener&lt;TStatefulService&gt; (this TStatefulService serviceImplementation, System.Fabric.StatefulServiceContext serviceContext) where TStatefulService : Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener&lt;(class Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, class Microsoft.ServiceFabric.Services.Remoting.IService) TStatefulService&gt;(!!TStatefulService serviceImplementation, class System.Fabric.StatefulServiceContext serviceContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatefulServiceContext)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateServiceRemotingListener(Of TStatefulService As {StatefulServiceBase, IService}) (serviceImplementation As TStatefulService, serviceContext As StatefulServiceContext) As IServiceRemotingListener" />
      <MemberSignature Language="F#" Value="static member CreateServiceRemotingListener : 'StatefulService * System.Fabric.StatefulServiceContext -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener (requires 'StatefulService :&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase and 'StatefulService :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener (serviceImplementation, serviceContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TStatefulService">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase</BaseTypeName>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceImplementation" Type="TStatefulService" RefType="this" />
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
      </Parameters>
      <Docs>
        <typeparam name="TStatefulService">Geben Sie die Einschränkung für die Dienst-Implementierung. Die dienstimplementierung muss abgeleitet <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" /> und eine oder mehrere Schnittstellen implementiert, die Ableitung <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> Schnittstelle.</typeparam>
        <param name="serviceImplementation">Eine zustandsbehaftete dienstimplementierung.</param>
        <param name="serviceContext">Der Kontext, unter dem der Dienst ausgeführt wird.</param>
        <summary>
            Eine Erweiterungsmethode, die erstellt eine <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für eine zustandsbehaftete dienstimplementierung. Dies ist als veraltet markierte-Implementierung. Verwenden Sie stattdessen diese CreateServiceRemotingReplicaListeners-Api
            </summary>
        <returns>Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> Kommunikation Listener diese Datenbanken die Schnittstellen abgeleitet <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> Schnittstelle.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener&lt;TStatelessService&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener&lt;TStatelessService&gt; (this TStatelessService serviceImplementation, System.Fabric.StatelessServiceContext serviceContext) where TStatelessService : Microsoft.ServiceFabric.Services.Runtime.StatelessService, Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener&lt;(class Microsoft.ServiceFabric.Services.Runtime.StatelessService, class Microsoft.ServiceFabric.Services.Remoting.IService) TStatelessService&gt;(!!TStatelessService serviceImplementation, class System.Fabric.StatelessServiceContext serviceContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatelessServiceContext)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateServiceRemotingListener(Of TStatelessService As {StatelessService, IService}) (serviceImplementation As TStatelessService, serviceContext As StatelessServiceContext) As IServiceRemotingListener" />
      <MemberSignature Language="F#" Value="static member CreateServiceRemotingListener : 'StatelessService * System.Fabric.StatelessServiceContext -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener (requires 'StatelessService :&gt; Microsoft.ServiceFabric.Services.Runtime.StatelessService and 'StatelessService :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener (serviceImplementation, serviceContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TStatelessService">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatelessService</BaseTypeName>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceImplementation" Type="TStatelessService" RefType="this" />
        <Parameter Name="serviceContext" Type="System.Fabric.StatelessServiceContext" />
      </Parameters>
      <Docs>
        <typeparam name="TStatelessService">Geben Sie die Einschränkung für die Dienst-Implementierung. Die dienstimplementierung muss abgeleitet <see cref="T:System.Fabric.Query.StatelessService" /> und eine oder mehrere Schnittstellen implementiert, die Ableitung <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> Schnittstelle.</typeparam>
        <param name="serviceImplementation">Eine zustandslose dienstimplementierung.</param>
        <param name="serviceContext">Der Kontext, unter dem der Dienst ausgeführt wird.</param>
        <summary>
            Eine Erweiterungsmethode, die erstellt eine <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für die Implementierung eines zustandslosen Diensts. Dies ist als veraltet markierte-Implementierung. Verwenden Sie stattdessen CreateServiceRemotingInstanceListeners Api.
            </summary>
        <returns>Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> Kommunikation Listener diese Datenbanken die Schnittstellen abgeleitet <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> Schnittstelle.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingReplicaListeners&lt;TStatefulService&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceRemotingReplicaListeners&lt;TStatefulService&gt; (this TStatefulService serviceImplementation) where TStatefulService : Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceRemotingReplicaListeners&lt;(class Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, class Microsoft.ServiceFabric.Services.Remoting.IService) TStatefulService&gt;(!!TStatefulService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingReplicaListeners``1(``0)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateServiceRemotingReplicaListeners(Of TStatefulService As {StatefulServiceBase, IService}) (serviceImplementation As TStatefulService) As IEnumerable(Of ServiceReplicaListener)" />
      <MemberSignature Language="F#" Value="static member CreateServiceRemotingReplicaListeners : 'StatefulService -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; (requires 'StatefulService :&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase and 'StatefulService :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingReplicaListeners serviceImplementation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TStatefulService">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase</BaseTypeName>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceImplementation" Type="TStatefulService" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="TStatefulService">To be added.</typeparam>
        <param name="serviceImplementation">Eine zustandsbehaftete dienstimplementierung.</param>
        <summary>
             Eine Erweiterungsmethode, die erstellt eine <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> für eine zustandsbehaftete dienstimplementierung.
             <typeparam name="TStatefulService">Geben Sie die Einschränkung für die Dienst-Implementierung. Die dienstimplementierung muss abgeleitet <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" /> und eine oder mehrere Schnittstellen implementiert, die Ableitung <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> Schnittstelle.</typeparam></summary>
        <returns>Ein <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> Kommunikation Listener diese Datenbanken die Schnittstellen abgeleitet <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> Schnittstelle.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>