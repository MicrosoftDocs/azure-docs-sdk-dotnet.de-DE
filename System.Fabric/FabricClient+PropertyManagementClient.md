<Type Name="FabricClient+PropertyManagementClient" FullName="System.Fabric.FabricClient+PropertyManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.PropertyManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/PropertyManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.PropertyManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.PropertyManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.PropertyManagementClient = class" />
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
      <para>Stellt die Eigenschaft Verwaltungsclient verwendet, um die Verwaltung von Namen und Eigenschaften ausführen.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateNameAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateNameAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.CreateNameAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNameAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateNameAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.CreateNameAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des Service Fabric.</para>
        </param>
        <summary>
          <para>Erstellt den angegebenen Service Fabric-Namen.</para>
        </summary>
        <returns>
          <para>Erstellungsvorgang für eine Aufgabe, die den asynchronen darstellt.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" />wird zurückgegeben, wenn die Service Fabric-Name ist bereits vorhanden.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateNameAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateNameAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.CreateNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.CreateNameAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des Service Fabric.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Erstellt den angegebenen Service Fabric-Namen.</para>
        </summary>
        <returns>
          <para>Erstellungsvorgang für eine Aufgabe, die den asynchronen darstellt.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" />wird zurückgegeben, wenn die Service Fabric-Name ist bereits vorhanden.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNameAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNameAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeleteNameAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteNameAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteNameAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeleteNameAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des Service Fabric.</para>
        </param>
        <summary>
          <para>Löscht den angegebenen Service Fabric-Namen an.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" />wird zurückgegeben, wenn <paramref name="name" /> übergeordnete Element eines anderen Namen, Eigenschaften oder eines Diensts ist.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNameAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNameAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeleteNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeleteNameAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des Service Fabric.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Löscht den angegebenen Service Fabric-Namen an.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" />wird zurückgegeben, wenn <paramref name="name" /> übergeordnete Element eines anderen Namen, Eigenschaften oder eines Diensts ist.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeletePropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePropertyAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePropertyAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeletePropertyAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeletePropertyAsync (parentName As Uri, propertyName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeletePropertyAsync : Uri * string -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeletePropertyAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der übergeordnete Service Fabric-Name der Eigenschaft.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <summary>
          <para>Löscht die angegebene Service Fabric-Eigenschaft.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeletePropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePropertyAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePropertyAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeletePropertyAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeletePropertyAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeletePropertyAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>URI definiert den übergeordneten Service Fabric-Namen der Eigenschaft.</para>
        </param>
        <param name="propertyName">
          <para>Zeichenfolge definiert den Namen der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="timeout">
          <para>
            <see cref="T:System.TimeSpan" />definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>
            <see cref="T:System.Threading.CancellationToken" />dass der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Löscht die angegebene Service Fabric-Eigenschaft.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumeratePropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync (Uri name, bool includeValues, System.Fabric.PropertyEnumerationResult previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync(class System.Uri name, bool includeValues, class System.Fabric.PropertyEnumerationResult previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumeratePropertiesAsync (name As Uri, includeValues As Boolean, previousResult As PropertyEnumerationResult) As Task(Of PropertyEnumerationResult)" />
      <MemberSignature Language="F#" Value="member this.EnumeratePropertiesAsync : Uri * bool * System.Fabric.PropertyEnumerationResult -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;" Usage="propertyManagementClient.EnumeratePropertiesAsync (name, includeValues, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="includeValues" Type="System.Boolean" />
        <Parameter Name="previousResult" Type="System.Fabric.PropertyEnumerationResult" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="includeValues">
          <para>
            <languageKeyword>"True"</languageKeyword> Wenn Werte mit den Metadaten zurückgegeben werden sollen. <languageKeyword>"False"</languageKeyword> zurückzugebenden nur Eigenschaftsmetadaten; <languageKeyword>"true"</languageKeyword> Eigenschaftsmetadaten und-Wert zurückgegeben.</para>
        </param>
        <param name="previousResult">
          <para>Das batchergebnis für den vorhergehenden Aufruf. Wenn dies der erste Aufruf, dieses Feld muss festgelegt werden auf Null.</para>
        </param>
        <summary>
          <para>Listet alle Service Fabric-Eigenschaften unter einem angegebenen Namen. </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</para>
          <para>Wenn <see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" /> ist "true", und klicken Sie dann das Ergebnis als Eingabe für den nächsten verwendet werden kann <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" /> aufrufen.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>    
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumeratePropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync (Uri name, bool includeValues, System.Fabric.PropertyEnumerationResult previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync(class System.Uri name, bool includeValues, class System.Fabric.PropertyEnumerationResult previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnumeratePropertiesAsync : Uri * bool * System.Fabric.PropertyEnumerationResult * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;" Usage="propertyManagementClient.EnumeratePropertiesAsync (name, includeValues, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="includeValues" Type="System.Boolean" />
        <Parameter Name="previousResult" Type="System.Fabric.PropertyEnumerationResult" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="includeValues">
          <para>
            <languageKeyword>"True"</languageKeyword> , wenn die Werte mit den Metadaten zurückgegeben werden sollen.
                <languageKeyword>"False"</languageKeyword> zurückzugebenden nur Eigenschaftsmetadaten; "true" zurückgeben Eigenschaftsmetadaten und-Wert.</para>
        </param>
        <param name="previousResult">
          <para>Das batchergebnis für den vorhergehenden Aufruf. Wenn dies der erste Aufruf, dieses Feld muss festgelegt werden auf Null.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Listet alle Service Fabric-Eigenschaften unter einem angegebenen Namen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</para>
          <para>Wenn <see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" /> ist "true", und klicken Sie dann das Ergebnis als Eingabe für den nächsten verwendet werden kann <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" /> aufrufen.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>    
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateSubNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync (Uri name, System.Fabric.NameEnumerationResult previousResult, bool recursive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync(class System.Uri name, class System.Fabric.NameEnumerationResult previousResult, bool recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateSubNamesAsync (name As Uri, previousResult As NameEnumerationResult, recursive As Boolean) As Task(Of NameEnumerationResult)" />
      <MemberSignature Language="F#" Value="member this.EnumerateSubNamesAsync : Uri * System.Fabric.NameEnumerationResult * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;" Usage="propertyManagementClient.EnumerateSubNamesAsync (name, previousResult, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.NameEnumerationResult" />
        <Parameter Name="recursive" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name der übergeordneten Service Fabric aufgelistet werden sollen.</para>
        </param>
        <param name="previousResult">
          <para>Das Ergebnis, das von der vorherigen Enumerate-Aufruf zurückgegeben wurde. Bei dem ersten Aufruf ist dies null.</para>
        </param>
        <param name="recursive">
          <para>
            <languageKeyword>"True"</languageKeyword> die Enumeration rekursiv sein soll.</para>
        </param>
        <summary>
          <para>Listet die Namen aller Service Fabric unter einem angegebenen Namen. </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt zählt Vorgang.</para>
          <para>Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NameEnumerationResult" />.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateSubNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync (Uri name, System.Fabric.NameEnumerationResult previousResult, bool recursive, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync(class System.Uri name, class System.Fabric.NameEnumerationResult previousResult, bool recursive, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnumerateSubNamesAsync : Uri * System.Fabric.NameEnumerationResult * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;" Usage="propertyManagementClient.EnumerateSubNamesAsync (name, previousResult, recursive, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.NameEnumerationResult" />
        <Parameter Name="recursive" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name der übergeordneten Service Fabric aufgelistet werden sollen.</para>
        </param>
        <param name="previousResult">
          <para>Das Ergebnis, das von der vorherigen Enumerate-Aufruf zurückgegeben wurde. Bei dem ersten Aufruf ist dies null.</para>
        </param>
        <param name="recursive">
          <para>
            <languageKeyword>"True"</languageKeyword> , wenn die Enumeration rekursiv sein soll.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Listet die Namen aller Service Fabric unter einem angegebenen Namen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt zählt Vorgang.</para>
          <para>Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NameEnumerationResult" />.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt; GetPropertyAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedProperty&gt; GetPropertyAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyAsync (parentName As Uri, propertyName As String) As Task(Of NamedProperty)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;" Usage="propertyManagementClient.GetPropertyAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der übergeordnete Service Fabric-Name der Eigenschaft.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <summary>
          <para>Ruft den angegebenen <see cref="T:System.Fabric.NamedProperty" /> ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</para>
          <para>Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NamedProperty" />.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt; GetPropertyAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedProperty&gt; GetPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;" Usage="propertyManagementClient.GetPropertyAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der übergeordnete Service Fabric-Name der Eigenschaft.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ruft den angegebenen <see cref="T:System.Fabric.NamedProperty" /> ab. </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</para>
          <para>Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NamedProperty" />.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyMetadataAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyMetadataAsync (parentName As Uri, propertyName As String) As Task(Of NamedPropertyMetadata)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyMetadataAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;" Usage="propertyManagementClient.GetPropertyMetadataAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der übergeordnete Service Fabric-Name der Eigenschaft.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Eigenschaft.</para>
        </param>
        <summary>
          <para>Ruft den angegebenen <see cref="T:System.Fabric.NamedPropertyMetadata" /> ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</para>
          <para>Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NamedPropertyMetadata" />.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyMetadataAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyMetadataAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;" Usage="propertyManagementClient.GetPropertyMetadataAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der übergeordnete Service Fabric-Name der Eigenschaft.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.
            Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ruft den angegebenen <see cref="T:System.Fabric.NamedPropertyMetadata" /> ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>    
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NameExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NameExistsAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NameExistsAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.NameExistsAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function NameExistsAsync (name As Uri) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameExistsAsync : Uri -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="propertyManagementClient.NameExistsAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des Service Fabric.</para>
        </param>
        <summary>
          <para>Gibt <languageKeyword>"true"</languageKeyword> , wenn der angegebene Name der Service Fabric ist vorhanden.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn der angegebene Service Fabric-Namen vorhanden ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
          <para>
            <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />ist der unidirektionale überprüfen, ob des Clusters aktiv ist und <see cref="T:System.Fabric.FabricClient" /> können mit dem Cluster verbinden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NameExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NameExistsAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NameExistsAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.NameExistsAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.NameExistsAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="propertyManagementClient.NameExistsAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des Service Fabric.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Gibt <languageKeyword>"true"</languageKeyword> , wenn der angegebene Name der Service Fabric ist vorhanden.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn der angegebene Service Fabric-Namen vorhanden ist, andernfalls <languageKeyword>"false"</languageKeyword>.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutCustomPropertyOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutCustomPropertyOperationAsync (Uri name, System.Fabric.PutCustomPropertyOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutCustomPropertyOperationAsync(class System.Uri name, class System.Fabric.PutCustomPropertyOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutCustomPropertyOperationAsync(System.Uri,System.Fabric.PutCustomPropertyOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutCustomPropertyOperationAsync (name As Uri, operation As PutCustomPropertyOperation) As Task" />
      <MemberSignature Language="F#" Value="member this.PutCustomPropertyOperationAsync : Uri * System.Fabric.PutCustomPropertyOperation -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutCustomPropertyOperationAsync (name, operation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="operation" Type="System.Fabric.PutCustomPropertyOperation" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="operation">
          <para>Die put-Vorgang-Parameter, einschließlich Namen, Wert und benutzerdefinierte Typinformationen.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft von beschriebenen <see cref="T:System.Fabric.PutCustomPropertyOperation" /> unter einem angegebenen Namen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="name" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutCustomPropertyOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutCustomPropertyOperationAsync (Uri name, System.Fabric.PutCustomPropertyOperation operation, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutCustomPropertyOperationAsync(class System.Uri name, class System.Fabric.PutCustomPropertyOperation operation, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutCustomPropertyOperationAsync(System.Uri,System.Fabric.PutCustomPropertyOperation,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutCustomPropertyOperationAsync : Uri * System.Fabric.PutCustomPropertyOperation * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutCustomPropertyOperationAsync (name, operation, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="operation" Type="System.Fabric.PutCustomPropertyOperation" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="operation">
          <para>Die put-Vorgang-Parameter, einschließlich Namen, Wert und benutzerdefinierte Typinformationen.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.
            Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft von beschriebenen <see cref="T:System.Fabric.PutCustomPropertyOperation" /> unter einem angegebenen Namen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="name" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Byte" /> Array unter einem angegebenen Namen. </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Double) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * double -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Double" /> unter einem angegebenen Namen.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * Guid -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Guid" /> unter einem angegebenen Namen. </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * int64 -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Int64" /> unter einem angegebenen Namen. </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As String) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * string -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.String" /> unter einem angegebenen Namen. </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, byte[] value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, unsigned int8[] value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.
            Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Byte" /> Array unter einem angegebenen Namen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, double value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, float64 value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Double,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * double * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Double" /> unter einem angegebenen Namen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, Guid value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.Guid value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.
            Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Guid" /> unter einem angegebenen Namen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, long value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, int64 value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Int64" /> unter einem angegebenen Namen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, string value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, string value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name des übergeordneten Service Fabric.</para>
        </param>
        <param name="propertyName">
          <para>Der Name der Service Fabric-Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Der Vorgang wurde beobachtet. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.String" /> unter einem angegebenen Namen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen stellt put Vorgang.</para>
        </returns>
        <remarks>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SubmitPropertyBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync (Uri parentName, System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync(class System.Uri parentName, class System.Collections.Generic.ICollection`1&lt;class System.Fabric.PropertyBatchOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitPropertyBatchAsync (parentName As Uri, operations As ICollection(Of PropertyBatchOperation)) As Task(Of PropertyBatchResult)" />
      <MemberSignature Language="F#" Value="member this.SubmitPropertyBatchAsync : Uri * System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;" Usage="propertyManagementClient.SubmitPropertyBatchAsync (parentName, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="operations" Type="System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name der übergeordneten Service Fabric unter dem die Eigenschaft Batchvorgänge ausgeführt werden.</para>
        </param>
        <param name="operations">
          <para>Die Eigenschaft Batchvorgänge.</para>
        </param>
        <summary>
          <para>Übermittelt einen Befehlsbatch <see cref="T:System.Fabric.PropertyBatchOperation" />.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</para>
          <para>Weitere Informationen finden Sie unter <see cref="T:System.Fabric.PropertyBatchResult" />.</para>
        </returns>
        <remarks>
          <para>Entweder alle oder keiner der Vorgänge im Batch werden ein Commit ausgeführt. </para>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn der Eigenschaftswert größer als 1 MB ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" />wird zurückgegeben, wenn mindestens ein Vorgang in den Benutzer bereitgestellten <paramref name="operations" /> ist fehlgeschlagen.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SubmitPropertyBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync (Uri parentName, System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; operations, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync(class System.Uri parentName, class System.Collections.Generic.ICollection`1&lt;class System.Fabric.PropertyBatchOperation&gt; operations, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SubmitPropertyBatchAsync : Uri * System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;" Usage="propertyManagementClient.SubmitPropertyBatchAsync (parentName, operations, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="operations" Type="System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>Der Name der übergeordneten Service Fabric unter dem die Eigenschaft Batchvorgänge ausgeführt werden.</para>
        </param>
        <param name="operations">
          <para>Die Eigenschaft Batchvorgänge.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Übermittelt einen Befehlsbatch <see cref="T:System.Fabric.PropertyBatchOperation" />s. Entweder alle oder keiner der Vorgänge im Batch werden ein Commit ausgeführt.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</para>
          <para>Weitere Informationen finden Sie unter <see cref="T:System.Fabric.PropertyBatchResult" />.</para>
        </returns>
        <remarks>
          <para>Entweder alle oder keiner der Vorgänge im Batch werden ein Commit ausgeführt. </para>
          <para>Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn der Eigenschaftswert größer als 1 MB ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" />wird zurückgegeben, wenn mindestens ein Vorgang in den Benutzer bereitgestellten <paramref name="operations" /> ist fehlgeschlagen.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>